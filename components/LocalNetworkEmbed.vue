<script setup lang="ts">
import { computed, onMounted, ref } from 'vue'

const props = withDefaults(defineProps<{
  src: string
  fallbackSrc: string
  title?: string
  label?: string
}>(), {
  title: 'Live product preview',
  label: 'Live product demo',
})

const canAttemptEmbed = ref(false)
const showLive = ref(false)

onMounted(() => {
  const sourceProtocol = new URL(props.src, window.location.href).protocol
  const blockedByMixedContent
    = window.location.protocol === 'https:' && sourceProtocol !== 'https:'

  canAttemptEmbed.value = !blockedByMixedContent
  showLive.value = canAttemptEmbed.value
})

const resolvedFallbackSrc = computed(() => {
  const value = props.fallbackSrc.trim()
  if (!value)
    return ''

  if (/^(?:[a-z]+:)?\/\//i.test(value) || value.startsWith('data:') || value.startsWith('blob:'))
    return value

  return `${import.meta.env.BASE_URL}${value.replace(/^\.?\//, '')}`
})
</script>

<template>
  <figure class="local-network-embed">
    <div class="local-network-embed__viewport">
      <iframe
        v-if="showLive"
        :src="src"
        :title="title"
        loading="eager"
        referrerpolicy="no-referrer"
        allow="microphone; autoplay; clipboard-write"
        allowfullscreen
      />

      <div
        v-else
        class="local-network-embed__fallback"
      >
        <img
          :src="resolvedFallbackSrc"
          :alt="`${title} screenshot`"
        >
      </div>
    </div>

    <figcaption>
      <span>{{ showLive ? label : 'Screenshot fallback' }}</span>
      <span class="local-network-embed__actions">
        <button
          v-if="canAttemptEmbed"
          type="button"
          @click="showLive = !showLive"
        >{{ showLive ? 'Use screenshot' : 'Try live preview' }}</button>
        <a
          :href="src"
          target="_blank"
          rel="noreferrer"
        >Open live app ↗</a>
      </span>
    </figcaption>
  </figure>
</template>

<style scoped>
.local-network-embed {
  display: grid;
  width: 100%;
  height: 100%;
  margin: 0;
  grid-template-rows: minmax(0, 1fr) auto;
  gap: 8px;
}

.local-network-embed__viewport {
  position: relative;
  min-height: 0;
  overflow: hidden;
  border: 1px solid rgba(247, 248, 250, 0.28);
  background: #12151a;
}

.local-network-embed iframe,
.local-network-embed__fallback,
.local-network-embed__fallback img {
  display: block;
  width: 100%;
  height: 100%;
}

.local-network-embed iframe {
  border: 0;
  background: #fff;
  width: 200%;
  height: 200%;
  transform: scale(0.5);
  transform-origin: top left;
}

.local-network-embed__fallback {
  position: relative;
}

.local-network-embed__fallback img {
  object-fit: contain;
  object-position: center;
}

figcaption {
  color: #aab2c0;
}

figcaption {
  display: flex;
  align-items: center;
  justify-content: space-between;
  gap: 16px;
  font-family: "SFMono-Regular", "Cascadia Code", "Roboto Mono", Menlo, Consolas, monospace;
  font-size: 10px;
  line-height: 1.2;
}

figcaption a {
  flex: none;
  color: #2f6bff;
  text-decoration: none;
}

.local-network-embed__actions {
  display: flex;
  flex: none;
  align-items: center;
  gap: 12px;
}

.local-network-embed__actions button {
  border: 0;
  padding: 0;
  background: transparent;
  color: #aab2c0;
  cursor: pointer;
  font: inherit;
}

.local-network-embed__actions button:hover,
figcaption a:hover {
  color: #f7f8fa;
}
</style>
