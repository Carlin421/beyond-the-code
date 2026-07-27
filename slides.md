---
theme: default
title: Beyond the Code
author: Carlin Hou
aspectRatio: 16/9
canvasWidth: 1280
colorSchema: dark
transition: fade
download: true
presenter: true
wakeLock: false
class: slide-cover
---

<div class="nyc-grid" aria-hidden="true"></div>

<a class="cover-logo-link" href="https://www.letsgoup.com/" target="_blank" rel="noreferrer" aria-label="Visit Universal Processing"><img src="/media/universal-processing-logo.png" alt="Universal Processing logo" /></a>

<main class="cover-content">
  <p class="cover-command"><span>carlin@nyc</span>:~$ ./internship-review</p>
  <h1>Beyond the Code</h1>
  <p class="cover-subtitle">What NYC and the AI Era Taught Me</p>
  <div class="accent-rule"></div>
  <div class="cover-identity">
    <strong>Carlin Hou</strong>
    <span>Software Engineering Intern</span>
    <span>Universal Processing · Summer 2026</span>
  </div>
</main>


---
class: slide-whoami
---

<header class="slide-header">
  <p class="kicker">00 / Before we begin</p>
  <h1><span class="prompt">$</span> whoami</h1>
</header>

<div class="whoami-layout">
  <div class="media-slot whoami-photo">
    <MediaFrame
      src="/media/carlin-portrait.jpg"
      alt="Portrait of Carlin Hou"
      label="Add your portrait"
      fit="cover"
      position="center 68%"
      aspect="4 / 5"
    />
  </div>
  <div class="whoami-copy">
    <section class="terminal-profile" aria-label="Carlin Hou profile">
      <div><span>name</span><strong>Carlin Hou</strong></div>
      <div><span>role</span><strong>Software Engineering Intern</strong></div>
      <div><span>team</span><strong>Universal Processing</strong></div>
      <div><span>current</span><strong>New York City</strong></div>
    </section>
    <section class="whoami-statement">
      <p>// background</p>
      <h2>My background combines business and information systems.</h2>
      <p class="whoami-detail">I connect technical decisions with users, operations, and company goals.</p>
    </section>
  </div>
</div>
<p class="previous-context"><span>Taiwan → New York City</span>: The environment changed quickly; my willingness to adapt did not.</p>
<footer class="slide-footer"><span>Carlin Hou · Internship Review</span><span>02</span></footer>


---
class: slide-routine
---

<header class="slide-header">
  <p class="kicker">01 / Day-to-day</p>
  <h1>My Best Work Starts Early</h1>
</header>

<div class="routine-layout">
  <section class="routine-lead">
    <p>// why the early start</p>
    <h2>Morning energy goes to the work that needs the clearest thinking.</h2>
    <p class="routine-detail">I’m usually in before 8:30—and often first at the office.</p>
  </section>

  <div class="routine-timeline" aria-label="A typical workday">
    <section>
      <span>before 08:30</span>
      <code>sync()</code>
      <div><h2>Taiwan handoff</h2><p>Email · chat · Jira · daily plan</p></div>
    </section>
    <section>
      <span>morning</span>
      <code>focus()</code>
      <div><h2>Deep work</h2><p>Demos · docs · architecture · code</p></div>
    </section>
    <section>
      <span>recurring</span>
      <code>align()</code>
      <div><h2>Team alignment</h2><p>Lewis (CTO) 1:1 · Taiwan engineers + PM weekly</p></div>
    </section>
    <section>
      <span>lunch</span>
      <code>reset()</code>
      <div><h2>Recharge</h2><p>Weekend meal prep · short nap</p></div>
    </section>
    <section>
      <span>afternoon</span>
      <code>verify()</code>
      <div><h2>Close the loop</h2><p>QA · docs · code review · plan check</p></div>
    </section>
  </div>
</div>

<p class="takeaway">Align early. Build deeply. Verify before leaving.</p>
<footer class="slide-footer"><span>Carlin Hou · Internship Review</span><span>03</span></footer>


---
class: slide-process
---

<header class="slide-header">
  <p class="kicker">02 / How I work</p>
  <h1>The Work Started Before the Code</h1>
</header>

<div class="process-stack">
  <div class="process-loop">
    <p class="code-caption">// product loop</p>
    <div class="workflow" aria-label="Context to feedback workflow">
      <span>context</span><b>|&gt;</b><span>requirements</span><b>|&gt;</b><span>jira</span><b>|&gt;</b><span>prototype</span><b>|&gt;</b><span>test</span><b>|&gt;</b><span>feedback</span><b>|&gt;</b><span>iterate</span>
    </div>
  </div>
  <div class="process-media-grid">
    <MediaFrame
      src="/media/jira-board.png"
      alt="Jira board showing internship projects moving from idea to testing"
      caption="Jira board · requirements become visible, trackable work"
      fit="contain"
      aspect="5 / 2"
    />
    <MediaFrame
      src="/media/weekly-notes.png"
      alt="Weekly project notes documenting feedback and next steps"
      caption="Weekly notes · decisions, feedback, and next steps"
      fit="contain"
      aspect="8 / 5"
    />
  </div>
</div>

<p class="takeaway">Development starts with shared understanding.</p>
<footer class="slide-footer"><span>Carlin Hou · Internship Review</span><span>04</span></footer>


---
class: slide-projects
---

<header class="slide-header">
  <p class="kicker">03 / The work</p>
  <h1>Each Project Started With a Real Bottleneck</h1>
</header>

<div class="project-columns">
  <article v-click>
    <span>01</span>
    <div><code>respond()</code><h2>Merchant Review Dashboard</h2></div>
    <div class="project-brief">
      <p><span>problem</span>Marketing manages Google and Yelp reviews across many merchant accounts.</p>
      <p><span>solution</span>One dashboard, AI replies, and owner approval for sensitive cases.</p>
    </div>
  </article>
  <article v-click>
    <span>02</span>
    <div><code>support()</code><h2>24/7 Support Assistant</h2></div>
    <div class="project-brief">
      <p><span>problem</span>Payment issues can happen after hours, when support may miss a call.</p>
      <p><span>solution</span>RAG chat answers first; phone intake routes a clearer case.</p>
    </div>
  </article>
  <article v-click>
    <span>03 / MVP</span>
    <div><code>coordinate()</code><h2>Salon Booking Assistant</h2></div>
    <div class="project-brief">
      <p><span>problem</span>Many salon merchants still schedule appointments with paper and pen.</p>
      <p><span>solution</span>One MVP for booking, staff, schedules, and resources.</p>
    </div>
  </article>
</div>

<p class="takeaway project-range">The goal: less waiting for merchants and less repetitive work for the team.</p>
<footer class="slide-footer"><span>Carlin Hou · Internship Review</span><span>05</span></footer>


---
class: slide-review
---

<header class="slide-header">
  <p class="kicker">Project 01 · Merchant review management</p>
  <h1>One Dashboard for Reviews Across Many Merchants</h1>
</header>

<div class="project-layout">
  <div class="media-slot project-media">
    <div class="embedded-site-frame">
      <iframe
        src="https://replymanager.userve.io/"
        title="ReplyManager live preview"
        loading="lazy"
        referrerpolicy="no-referrer"
        allowfullscreen
      ></iframe>
      <p class="embedded-link">
        Live link:
        <a href="https://replymanager.userve.io/" target="_blank" rel="noreferrer">replymanager.userve.io</a>
      </p>
    </div>
  </div>
  <div class="project-story">
    <p class="code-caption">// problem → solution → value</p>
    <div class="impact-story">
      <p><span>problem</span>Marketing manages Google and Yelp reviews across many merchant accounts.</p>
      <p><span>solution</span>One dashboard tracks merchants; AI posts routine replies and routes negative cases to the owner.</p>
      <p><span>value</span>Fewer account switches, faster routine replies, and safer handling of sensitive reviews.</p>
    </div>
    <div class="compact-code-flow" aria-label="Review response workflow">
      <code>collect()</code><b>→</b><code>draft()</code><b>→</b><code>owner_check()</code><b>→</b><code>post()</code>
    </div>
    <div class="project-evidence">
      <p><span>contribution</span>Dashboard · merchant stats · AI replies · approval flow</p>
      <p><span>next</span>Revise with MKT feedback · prepare daily workflow</p>
    </div>
  </div>
</div>

<footer class="slide-footer"><span>Carlin Hou · Internship Review</span><span>06</span></footer>


---
class: slide-rag
---

<header class="slide-header">
  <p class="kicker">Project 02 · 24/7 merchant support</p>
  <h1>Support Problems Don’t Wait for Office Hours</h1>
</header>

<div class="rag-layout">
  <div class="rag-copy">
    <p class="code-caption">// problem → solution → value</p>
    <div class="impact-story">
      <p><span>problem</span>Payment issues can happen at any hour; a missed call can mean lost sales.</p>
      <p><span>solution</span>RAG searches company documents first; phone intake clarifies and routes the issue.</p>
      <p><span>value</span>A path toward 24/7 first response, clearer cases, and faster document search.</p>
    </div>
    <div class="compact-code-flow" aria-label="Retrieval augmented generation workflow">
      <code>question</code><b>→</b><code>retrieve(docs)</code><b>→</b><code>answer_or_escalate()</code>
    </div>
    <div class="project-evidence rag-evidence">
      <p><span>contribution</span>Structured knowledge · RAG · phone intake · evaluation</p>
      <p><span>next</span>CRM connection · more real support data</p>
    </div>
    <p class="takeaway">The goal: merchants get a first response; support gets a clearer case.</p>
  </div>
  <div class="media-slot project-media">
    <div class="embedded-site-frame">
      <iframe
        src="https://csagent.userve.io/"
        title="CSAgent live preview"
        loading="lazy"
        referrerpolicy="no-referrer"
        allowfullscreen
      ></iframe>
      <p class="embedded-link">
        Live link:
        <a href="https://csagent.userve.io/" target="_blank" rel="noreferrer">csagent.userve.io</a>
      </p>
    </div>
  </div>
</div>

<footer class="slide-footer"><span>Carlin Hou · Internship Review</span><span>07</span></footer>


---
class: slide-booking
---

<header class="slide-header">
  <p class="kicker">Project 03 · Salon booking · MVP</p>
  <h1>Replace Paper Scheduling With One Booking System</h1>
</header>

<div class="booking-story">
  <p><span>problem</span>Many salon merchants still manage appointments with paper and pen.</p>
  <p><span>solution / MVP</span>Plan one system for chat, phone, appointments, staff, and resources.</p>
</div>

<div class="booking-map">
  <div class="constraint constraint-a"><span>service.duration</span><span>employee.skills</span><span>staff.schedule</span><span>multiService[]</span><span>addOns</span></div>
  <div class="media-slot booking-media">
    <MediaFrame
      src="/media/salon-booking.png"
      alt="Salon booking assistant interface"
      label="Current MVP interface · mock data"
      fit="contain"
      aspect="4 / 3"
    />
  </div>
  <div class="constraint constraint-b"><span>room</span><span>equipment</span><span>owner.admin</span><span>planned.chat</span><span>planned.phone</span></div>
</div>

<p class="takeaway">Two-week MVP: prove the scheduling rules before building the full system.</p>
<footer class="slide-footer"><span>Carlin Hou · Internship Review</span><span>08</span></footer>


---
class: slide-evolution
---

<header class="slide-header">
  <p class="kicker">04 / How the tools changed</p>
  <h1>How My Use of AI Changed</h1>
</header>

<div class="evolution">
  <section>
    <span>v1.0</span>
    <h2>College</h2>
    <code>AI as a search tool</code>
    <p>Samples + Stack Overflow.</p>
  </section>
  <b>→</b>
  <section>
    <span>v2.0</span>
    <h2>Internship in Taiwan</h2>
    <code>AI as a coding partner</code>
    <p>Specific tasks. Limited context.</p>
  </section>
  <b>→</b>
  <section>
    <span>v3.0</span>
    <h2>New York City</h2>
    <code>AI inside a complete product process</code>
    <p>Specs. Steps. Review. Feedback.</p>
  </section>
</div>

<p class="takeaway">The developer’s role is shifting from producing more code to making better decisions.</p>
<footer class="slide-footer"><span>Carlin Hou · Internship Review</span><span>09</span></footer>


---
class: slide-bottleneck
---

<p class="kicker">// central lesson</p>
<h1 class="bottleneck-title">The Bottleneck Moved.</h1>

<div v-click="1" class="comparison" aria-label="Before and AI era comparison">
  <div class="comparison-head"><span>Before</span><span>In the AI Era</span></div>
  <div><span>Writing code</span><span>Defining the right problem</span></div>
  <div><span>Implementation speed</span><span>Clear requirements</span></div>
  <div><span>Technical execution</span><span>Human judgment</span></div>
  <div><span>Feature delivery</span><span>Product alignment</span></div>
  <div><span>Individual output</span><span>Shared knowledge</span></div>
</div>

<p v-click="2" class="final-reveal">Speed creates value only when the team shares a clear destination.</p>
<footer class="slide-footer"><span>Carlin Hou · Internship Review</span><span>10</span></footer>


---
class: slide-closing
---

<div class="closing-grid" aria-hidden="true"></div>

<div class="closing-layout">
  <main>
    <p class="closing-journey">This summer changed how I think<br><span>about building useful products.</span></p>
    <h1>Still learning.<br>Still building.<br>Still halfway.</h1>
    <p class="thanks">With thanks to Taipei City, Universal Processing, the engineers, coworkers, and interns who shaped this summer.</p>
    <p class="thank-you">Thank you.</p>
  </main>
  <div class="media-slot closing-media">
    <MediaFrame
      src="/media/team-lunch.jpg"
      alt="Universal Processing team lunch"
      label="Add team lunch photo"
      fit="cover"
      position="center"
      aspect="4 / 3"
    />
  </div>
</div>
