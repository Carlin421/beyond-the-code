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
  <h1>Beyond the Code</h1>
  <p class="cover-subtitle">Three AI Products I Built at Universal Processing</p>
  <div class="accent-rule"></div>
  <div class="cover-identity">
    <strong>Carlin Hou</strong>
    <span>Software Engineering Intern</span>
    <span>Universal Processing</span>
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
      label="Carlin Hou · New York City"
      fit="cover"
      position="center 68%"
      aspect="4 / 5"
    />
  </div>
  <section class="whoami-statement">
    <p>Business + information systems background</p>
    <h2>I connect user needs, business workflows, and engineering.</h2>
  </section>
</div>
<footer class="slide-footer"><span>Carlin Hou · Internship Review</span><span>02</span></footer>


---
class: slide-routine
---

<header class="slide-header">
  <p class="kicker">01 / Day-to-day</p>
  <h1>How I Move Work Forward</h1>
</header>

<div class="routine-layout">
  <section class="routine-lead">
    <p>// stay aligned</p>
    <h2>Context first. Decisions second. Then I build.</h2>
    <p class="routine-detail">Lewis (CTO) 1:1 + weekly Taiwan engineering and PM sync.</p>
  </section>

  <div class="routine-timeline" aria-label="A typical workday">
    <section>
      <span>start</span>
      <code>sync()</code>
      <div><h2>Align</h2><p>Taiwan updates · Jira · priorities</p></div>
    </section>
    <section>
      <span>focus</span>
      <code>build()</code>
      <div><h2>Build</h2><p>Product decisions · architecture · code · demos</p></div>
    </section>
    <section>
      <span>finish</span>
      <code>verify()</code>
      <div><h2>Verify</h2><p>QA · code review · documentation · feedback</p></div>
    </section>
  </div>
</div>

<p class="takeaway">Context → decision → build → feedback.</p>
<footer class="slide-footer"><span>Carlin Hou · Internship Review</span><span>03</span></footer>


---
class: slide-process
---

<header class="slide-header">
  <p class="kicker">02 / How I work</p>
  <h1>From Business Problem to Working Product</h1>
</header>

<div class="process-stack">
  <div class="process-loop">
    <p class="code-caption">// product loop</p>
    <div class="process-questions" aria-label="Questions before implementation">
      <span>Who does the work?</span>
      <span>Where does it stall?</span>
      <span>What can go wrong?</span>
    </div>
    <div class="workflow" aria-label="Context to feedback workflow">
      <span>understand</span><b>|&gt;</b><span>specify</span><b>|&gt;</b><span>build</span><b>|&gt;</b><span>test</span><b>|&gt;</b><span>improve</span>
    </div>
  </div>
  <div class="process-media-grid">
    <MediaFrame
      src="/media/jira-board.png"
      alt="Jira board showing internship projects moving from idea to testing"
      fit="contain"
      aspect="5 / 2"
    />
  </div>
</div>

<p class="takeaway">Clear structure keeps AI focused on the right product.</p>
<footer class="slide-footer"><span>Carlin Hou · Internship Review</span><span>04</span></footer>


---
class: slide-projects
---

<header class="slide-header">
  <p class="kicker">03 / The work</p>
  <h1>Three Problems. Three AI Products.</h1>
</header>

<div class="project-columns">
  <article v-click>
    <span>01</span>
    <div><h2>AI Review Manager</h2><p class="project-status">in testing</p></div>
    <div class="project-brief">
      <p>Manage multi-merchant reviews and route sensitive replies for approval.</p>
    </div>
  </article>
  <article v-click>
    <span>02</span>
    <div><h2>AI Technical Support</h2><p class="project-status">in testing</p></div>
    <div class="project-brief">
      <p>Answer from trusted company documents and hand off uncertain cases.</p>
    </div>
  </article>
  <article v-click>
    <span>03</span>
    <div><h2>AI Salon Booking</h2><p class="project-status">working end to end</p></div>
    <div class="project-brief">
      <p>Match services, staff, resources, and live availability in one booking.</p>
    </div>
  </article>
</div>

<p class="takeaway project-range">Built around real team and merchant workflows.</p>
<footer class="slide-footer"><span>Carlin Hou · Internship Review</span><span>05</span></footer>


---
class: slide-review
---

<header class="slide-header">
  <p class="kicker">Project 01</p>
  <h1>AI Review Manager</h1>
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
    <h2 class="project-claim">Faster replies without risking each merchant’s voice.</h2>
    <div class="impact-story">
      <p><span>problem</span>Marketing manages Google and Yelp reviews across many accounts, but every merchant has a different voice.</p>
      <p><span>I built</span>One dashboard, merchant-specific AI drafts, and approval for sensitive replies.</p>
      <p><span>result</span>Working in testing; Marketing feedback is shaping the release.</p>
    </div>
  </div>
</div>

<footer class="slide-footer"><span>Carlin Hou · Internship Review</span><span>06</span></footer>


---
class: slide-rag
---

<header class="slide-header">
  <p class="kicker">Project 02</p>
  <h1>AI Technical Support</h1>
</header>

<div class="rag-layout">
  <div class="rag-copy">
    <h2 class="project-claim">24/7 first help, grounded in company knowledge.</h2>
    <div class="impact-story">
      <p><span>problem</span>Payment issues happen anytime, but useful answers are scattered across documents.</p>
      <p><span>I built</span>Trusted-document retrieval, clarification, and a clear human handoff.</p>
      <p><span>result</span>Working in testing; phone and CRM integration come next.</p>
    </div>
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
  <p class="kicker">Project 03</p>
  <h1>AI Salon Booking</h1>
</header>

<h2 class="project-claim booking-claim">One system coordinates the entire appointment.</h2>

<div class="booking-focus">
  <div class="booking-summary">
    <p class="booking-request"><span>customer</span>“I need a gel manicure with nail art this Saturday afternoon.”</p>
    <div class="impact-story">
      <p><span>I built</span>Booking rules, matching, live availability, customer chat, and owner admin.</p>
      <p><span>status</span>Working end to end; merchant validation is next.</p>
    </div>
  </div>
  <div class="media-slot booking-media">
    <LocalNetworkEmbed
      src="https://age-copper-theft-cognitive.trycloudflare.com"
      fallback-src="/media/salon-booking.png"
      title="Salon booking product live preview"
      label="Working end-to-end product · merchant validation next"
    />
  </div>
</div>

<p class="takeaway">From natural request to confirmed booking.</p>
<footer class="slide-footer"><span>Carlin Hou · Internship Review</span><span>08</span></footer>


---
class: slide-evolution
---

<header class="slide-header">
  <p class="kicker">04 / How AI changed my work</p>
  <h1>How AI Changed the Way I Work</h1>
</header>

<div class="ai-evolution" aria-label="How Carlin's use of AI evolved">
  <section>
    <span>before</span>
    <h2>Search</h2>
    <p>Samples, documentation, and Stack Overflow.</p>
  </section>
  <b>→</b>
  <section>
    <span>then</span>
    <h2>Assist</h2>
    <p>Specific questions and small coding tasks.</p>
  </section>
  <b>→</b>
  <section>
    <span>now</span>
    <h2>Direct</h2>
    <p>I define, structure, and review; AI implements.</p>
  </section>
</div>

<p class="takeaway">Less time writing every line. More time owning the product.</p>
<footer class="slide-footer"><span>Carlin Hou · Internship Review</span><span>09</span></footer>


---
class: slide-judgment
---

<header class="slide-header">
  <p class="kicker">05 / Reflection</p>
  <h1>The Hard Part Is Deciding What AI Should Control</h1>
</header>

<div class="judgment-list" aria-label="The AI boundary in each product">
  <div><span>AI Review Manager</span><h2>People approve reputational risk.</h2></div>
  <div><span>AI Technical Support</span><h2>Trusted documents first; humans take uncertain cases.</h2></div>
  <div><span>AI Salon Booking</span><h2>System rules control real availability.</h2></div>
</div>

<p class="takeaway">AI can produce code. I own the product decisions and the result.</p>
<footer class="slide-footer"><span>Carlin Hou · Internship Review</span><span>10</span></footer>


---
class: slide-closing
---

<div class="closing-grid" aria-hidden="true"></div>

<div class="closing-layout">
  <main>
    <h1>I turn messy workflows into AI products people can trust.</h1>
    <p class="closing-next">I’m ready to keep building what comes next.</p>
    <p class="thanks">With thanks to Universal Processing, Taipei City, the engineers, coworkers, and interns who shaped this summer.</p>
    <p class="thank-you">Thank you.</p>
  </main>
  <div class="media-slot closing-media">
    <MediaFrame
      src="/media/team-lunch.jpg"
      alt="Universal Processing team lunch"
      label="Team lunch · New York City"
      fit="cover"
      position="center"
      aspect="4 / 3"
    />
  </div>
</div>
