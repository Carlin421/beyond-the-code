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
  <p class="cover-subtitle">What Building Three AI Products Taught Me</p>
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
      label="Carlin Hou · New York City"
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
      <p class="whoami-detail">I look at product decisions from both the user and engineering sides.</p>
    </section>
  </div>
</div>
<p class="previous-context"><span>Technical internships</span> taught me to build; startup work taught me to ask who needs it—and why.</p>
<footer class="slide-footer"><span>Carlin Hou · Internship Review</span><span>02</span></footer>


---
class: slide-routine
---

<header class="slide-header">
  <p class="kicker">01 / Day-to-day</p>
  <h1>My Day Connects New York and Taiwan</h1>
</header>

<div class="routine-layout">
  <section class="routine-lead">
    <p>// start with context</p>
    <h2>Before I build, I decide what will move the product forward.</h2>
    <p class="routine-detail">I arrive before 8:30, read Taiwan updates, and set the day’s priority.</p>
  </section>

  <div class="routine-timeline" aria-label="A typical workday">
    <section>
      <span>before 08:30</span>
      <code>sync()</code>
      <div><h2>Taiwan updates</h2><p>Email · chat · Jira · priorities</p></div>
    </section>
    <section>
      <span>morning</span>
      <code>build()</code>
      <div><h2>Product + engineering</h2><p>Architecture · code · demos · documentation</p></div>
    </section>
    <section>
      <span>recurring</span>
      <code>align()</code>
      <div><h2>Cross-team decisions</h2><p>Lewis 1:1 · Taiwan engineers + PM · user-team calls</p></div>
    </section>
    <section>
      <span>afternoon</span>
      <code>verify()</code>
      <div><h2>Test and learn</h2><p>QA · feedback · code review · next steps</p></div>
    </section>
  </div>
</div>

<p class="takeaway">Product decisions → engineering → testing → feedback.</p>
<footer class="slide-footer"><span>Carlin Hou · Internship Review</span><span>03</span></footer>


---
class: slide-process
---

<header class="slide-header">
  <p class="kicker">02 / How I work</p>
  <h1>I Turned Unclear Needs Into Buildable Systems</h1>
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
      <span>workflow</span><b>|&gt;</b><span>requirements</span><b>|&gt;</b><span>system_design</span><b>|&gt;</b><span>tasks</span><b>|&gt;</b><span>prototype</span><b>|&gt;</b><span>test</span><b>|&gt;</b><span>feedback</span>
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

<p class="takeaway">Clear structure keeps engineers—and AI—from building the wrong product faster.</p>
<footer class="slide-footer"><span>Carlin Hou · Internship Review</span><span>04</span></footer>


---
class: slide-projects
---

<header class="slide-header">
  <p class="kicker">03 / The work</p>
  <h1>Three Problems. Three Products.</h1>
</header>

<div class="project-columns">
  <article v-click>
    <span>01</span>
    <div><code>respond()</code><h2>Merchant Review Dashboard</h2><p class="project-status">working · testing + revision</p></div>
    <div class="project-brief">
      <p><span>problem</span>Marketing manages Google and Yelp reviews across many merchant accounts.</p>
      <p><span>solution</span>AI drafts in each merchant’s voice; sensitive reviews require owner approval.</p>
    </div>
  </article>
  <article v-click>
    <span>02</span>
    <div><code>support()</code><h2>24/7 Support Assistant</h2><p class="project-status">working · testing</p></div>
    <div class="project-brief">
      <p><span>problem</span>Payment questions arrive after hours; trusted answers are scattered across documents.</p>
      <p><span>solution</span>The assistant searches company knowledge first, then clarifies or hands off.</p>
    </div>
  </article>
  <article v-click>
    <span>03</span>
    <div><code>coordinate()</code><h2>Salon Booking Product</h2><p class="project-status">working end to end · validation next</p></div>
    <div class="project-brief">
      <p><span>problem</span>Booking depends on services, skills, schedules, rooms, and resources—not just an open time.</p>
      <p><span>solution</span>One engine connects natural conversation, availability, and owner controls.</p>
    </div>
  </article>
</div>

<p class="takeaway project-range">Automate repetition without removing human judgment.</p>
<footer class="slide-footer"><span>Carlin Hou · Internship Review</span><span>05</span></footer>


---
class: slide-review
---

<header class="slide-header">
  <p class="kicker">Project 01 · Merchant review management</p>
  <h1>AI Handles Repetition. People Protect Reputation.</h1>
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
      <p><span>problem</span>Marketing manages Google and Yelp reviews across many accounts, but every merchant has a different voice.</p>
      <p><span>solution</span>AI drafts routine replies in that voice; sensitive reviews require owner context and approval.</p>
      <p><span>value</span>Less account switching, faster routine replies, and safer handling of reputational risk.</p>
    </div>
    <div class="compact-code-flow" aria-label="Review response workflow">
      <code>collect()</code><b>→</b><code>tone_draft()</code><b>→</b><code>risk_check()</code><b>→</b><code>post_or_approve()</code>
    </div>
    <div class="project-evidence">
      <p><span>built</span>Dashboard · merchant stats · tone-aware drafts · approval flow</p>
      <p><span>today</span>Working in testing · MKT feedback guides revisions</p>
      <p><span>next</span>Measure response time · edit rate · approval turnaround</p>
    </div>
  </div>
</div>

<footer class="slide-footer"><span>Carlin Hou · Internship Review</span><span>06</span></footer>


---
class: slide-rag
---

<header class="slide-header">
  <p class="kicker">Project 02 · 24/7 merchant support</p>
  <h1>Trusted Answer—or a Clear Human Handoff</h1>
</header>

<div class="rag-layout">
  <div class="rag-copy">
    <p class="code-caption">// problem → solution → value</p>
    <div class="impact-story">
      <p><span>problem</span>Payment problems can happen at any hour, while useful answers are scattered across company documents.</p>
      <p><span>solution</span>The assistant searches trusted documents first; if unsure, it clarifies and hands off a clearer case.</p>
      <p><span>value</span>Faster first help, less searching, and a better-informed support handoff.</p>
    </div>
    <div class="compact-code-flow" aria-label="Retrieval augmented generation workflow">
      <code>question</code><b>→</b><code>trusted_docs</code><b>→</b><code>answer_or_clarify</code><b>→</b><code>human_handoff</code>
    </div>
    <div class="project-evidence rag-evidence">
      <p><span>built</span>Structured knowledge · retrieval · clarification · handoff flow</p>
      <p><span>today</span>Working in testing · grounded answers + source checks</p>
      <p><span>next</span>Stronger phone + CRM integration · real support data</p>
    </div>
    <p class="takeaway">What matters is the handoff, not just the chat screen.</p>
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
  <p class="kicker">Project 03 · Working end to end in two weeks</p>
  <h1>One Conversation Coordinates the Entire Booking</h1>
</header>

<div class="booking-story">
  <p><span>customer</span>“I need a gel manicure with nail art this Saturday afternoon.”</p>
  <p><span>system</span>One engine asks follow-ups, checks real rules, and confirms the booking.</p>
</div>

<div class="booking-map">
  <div class="constraint constraint-a"><span>service + duration</span><span>employee skills</span><span>staff schedule</span><span>multiple services</span><span>add-ons</span></div>
  <div class="media-slot booking-media">
    <LocalNetworkEmbed
      src="https://age-copper-theft-cognitive.trycloudflare.com"
      fallback-src="/media/salon-booking.png"
      title="Salon booking product live preview"
      label="Working end-to-end product · merchant validation next"
    />
  </div>
  <div class="constraint constraint-b"><span>room + equipment</span><span>live availability</span><span>web + chat</span><span>owner admin</span><span>confirmation</span></div>
</div>

<p class="takeaway">I owned the rules, matching, availability, admin, and customer experience.</p>
<footer class="slide-footer"><span>Carlin Hou · Internship Review</span><span>08</span></footer>


---
class: slide-judgment
---

<header class="slide-header">
  <p class="kicker">04 / How AI changed the work</p>
  <h1>The Bottleneck Moved to Judgment</h1>
</header>

<div class="judgment-layout">
  <section class="judgment-questions" aria-label="Three questions for AI product decisions">
    <p class="code-caption">// the hard questions</p>
    <div><span>01</span><h2>Where should automation stop?</h2></div>
    <div><span>02</span><h2>What information should AI trust?</h2></div>
    <div><span>03</span><h2>What happens when AI is uncertain?</h2></div>
  </section>

  <section class="judgment-answers" aria-label="The boundary in each product">
    <p class="code-caption">// the boundaries I chose</p>
    <div><span>reviews</span><h2>People control reputational risk.</h2></div>
    <div><span>support</span><h2>Trusted documents first; human handoff when uncertain.</h2></div>
    <div><span>booking</span><h2>The availability engine controls reservations.</h2></div>
  </section>
</div>

<div class="judgment-shift" aria-label="How the engineering bottleneck changed">
  <p><span>before</span>“Can we write this?”</p>
  <b>→</b>
  <p><span>now</span>“Do we understand it well enough?”</p>
</div>

<p class="takeaway">I connect users, business workflows, and technical systems—and own the result.</p>
<footer class="slide-footer"><span>Carlin Hou · Internship Review</span><span>09</span></footer>


---
class: slide-closing
---

<div class="closing-grid" aria-hidden="true"></div>

<div class="closing-layout">
  <main>
    <p class="closing-journey">I began with a narrow idea of engineering.<br><span>Now I see the full product loop.</span></p>
    <h1>I want to turn messy problems into products people can trust.</h1>
    <p class="closing-next">One month left to move these products closer to daily use.</p>
    <p class="thanks">With thanks to Taipei City, Universal Processing, the engineers, coworkers, and interns who shaped this summer.</p>
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
