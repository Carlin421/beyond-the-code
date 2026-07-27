<script setup lang="ts">
import { computed, ref, watch } from 'vue'

type MediaFit = 'cover' | 'contain'

const props = withDefaults(defineProps<{
  src?: string
  alt?: string
  label?: string
  caption?: string
  fit?: MediaFit
  position?: string
  aspect?: string
}>(), {
  src: '',
  alt: '',
  label: 'Add image',
  caption: '',
  fit: 'cover',
  position: 'center',
  aspect: '16 / 9',
})

const failed = ref(false)

watch(() => props.src, () => {
  failed.value = false
})

const resolvedSrc = computed(() => {
  const value = props.src.trim()
  if (!value)
    return ''

  if (/^(?:[a-z]+:)?\/\//i.test(value) || value.startsWith('data:') || value.startsWith('blob:'))
    return value

  const relativePath = value.replace(/^\.?\//, '')
  return `${import.meta.env.BASE_URL}${relativePath}`
})

const showImage = computed(() => Boolean(resolvedSrc.value) && !failed.value)
const accessibleLabel = computed(() => props.alt || props.label)
</script>

<template>
  <figure
    class="media-frame"
    :style="{ '--media-aspect': aspect }"
  >
    <div class="media-frame__surface">
      <img
        v-if="showImage"
        class="media-frame__image"
        :src="resolvedSrc"
        :alt="alt"
        :style="{ objectFit: fit, objectPosition: position }"
        @error="failed = true"
      >

      <div
        v-else
        class="media-frame__placeholder"
        role="img"
        :aria-label="accessibleLabel"
      >
        <span class="media-frame__label">{{ label }}</span>
        <span
          v-if="src"
          class="media-frame__path"
        >{{ src }}</span>
      </div>
    </div>

    <figcaption
      v-if="caption"
      class="media-frame__caption"
    >
      {{ caption }}
    </figcaption>
  </figure>
</template>

<style scoped>
.media-frame {
  display: grid;
  width: 100%;
  margin: 0;
  gap: 0.55rem;
}

.media-frame__surface {
  position: relative;
  width: 100%;
  aspect-ratio: var(--media-aspect);
  overflow: hidden;
  background: #f5f3ee;
  border: 1px solid rgba(27, 36, 48, 0.16);
  border-radius: 0.35rem;
}

.media-frame__image {
  display: block;
  width: 100%;
  height: 100%;
}

.media-frame__placeholder {
  box-sizing: border-box;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  width: 100%;
  height: 100%;
  padding: 1.5rem;
  gap: 0.45rem;
  color: #68707a;
  text-align: center;
  border: 1px dashed rgba(27, 36, 48, 0.28);
}

.media-frame__label {
  color: #35404b;
  font-size: 0.92rem;
  font-weight: 600;
  letter-spacing: 0.01em;
}

.media-frame__path {
  max-width: 100%;
  overflow-wrap: anywhere;
  font-family: ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  font-size: 0.63rem;
  opacity: 0.78;
}

.media-frame__caption {
  color: #68707a;
  font-size: 0.66rem;
  line-height: 1.35;
}
</style>
