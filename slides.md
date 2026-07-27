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

<!--
Timing: 0:20

Good afternoon. I’m Carlin Hou, a software engineering intern at Universal Processing. Today I want to go beyond a list of features. I’ll share three AI projects, the business problems behind them, what I personally contributed, and how AI has changed the way I work as an engineer.

[Sources]
- User-provided internship brief, accessed 2026-07-24.
- User-provided Universal Processing logo, accessed 2026-07-27.
- Universal Processing official website, https://www.letsgoup.com/, accessed 2026-07-27.
-->

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

<!--
Timing: 0:45

Before the projects, here is a little context about me. My background combines business and information systems, so I naturally look at software from two sides: how it works, and how it supports users, operations, and company goals. A few months before this internship, I was finishing military service in Taiwan and doing interviews late at night. Then I arrived in New York and joined Universal Processing. The environment changed quickly, but my willingness to adapt did not. That journey is only a small part of the story. The rest is about how I translated business needs into products the team could discuss, test, and improve.

[Sources]
- User-provided internship brief, accessed 2026-07-24.
- User-provided photograph, IMG_3259.jpeg, accessed 2026-07-27.
-->

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

<!--
Timing: 0:40

I usually arrive before 8:30—often the first one there—because I’m a morning person. I begin with email, chat, and Jira, catching the overnight handoff from Taiwan and setting my plan. Before meetings, I prepare demos or documentation. Morning is my best focus time, so I use it for architecture and coding. At lunch, I eat the meal I prepared over the weekend and take a short nap. The afternoon is for QA, organizing and documenting work, then code review, more coding, and a final check against the plan.

[Sources]
- User-provided description of a typical workday, accessed 2026-07-27.
-->

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

<!--
Timing: 0:45

For me, each project started before the code. I reviewed the business problem, clarified open requirements, and translated the work into Jira tasks. The board made ownership and progress visible. Weekly notes recorded decisions, feedback, and what had to happen next. Then I built prototypes, tested them, and showed progress in meetings. Sharing work early helped the team correct assumptions before we invested more time. Feedback was not the final step; it became part of every development cycle. That process helped turn an unclear request into work the team could discuss, test, and improve together.

[Sources]
- User-provided internship brief, accessed 2026-07-24.
- User-provided Jira board screenshot, accessed 2026-07-27.
- User-provided weekly project-notes screenshot, accessed 2026-07-27.
-->

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
    <div><code>generate()</code><h2>AI Review Assistant</h2></div>
    <div class="project-brief">
      <p><span>problem</span>Replies take time and still require judgment.</p>
      <p><span>solution</span>AI drafts; a person reviews.</p>
    </div>
  </article>
  <article v-click>
    <span>02</span>
    <div><code>retrieve()</code><h2>Internal Support Chatbot</h2></div>
    <div class="project-brief">
      <p><span>problem</span>Answers are scattered across documents and past cases.</p>
      <p><span>solution</span>Search trusted knowledge before answering.</p>
    </div>
  </article>
  <article v-click>
    <span>03 / MVP</span>
    <div><code>coordinate()</code><h2>Salon Booking Assistant</h2></div>
    <div class="project-brief">
      <p><span>problem</span>A booking depends on staff, time, rooms, and equipment.</p>
      <p><span>solution</span>Check every rule before proposing a slot.</p>
    </div>
  </article>
</div>

<p class="takeaway project-range">The common goal: less repetitive work, faster answers, and fewer manual checks.</p>
<footer class="slide-footer"><span>Carlin Hou · Internship Review</span><span>05</span></footer>

<!--
Timing: 0:35

These projects started with three familiar kinds of friction. Review replies take time, but they still need human judgment. Internal answers exist, but people lose time searching across documents and old cases. Salon booking looks simple until staff, rooms, equipment, and service timing all have to match. The solutions were different: draft with human review, retrieve trusted knowledge before answering, and validate booking rules before suggesting a time. The common goal was practical—reduce repetitive work, make answers easier to reach, and remove manual checks where the product could handle them safely.

[Sources]
- User-provided internship brief, accessed 2026-07-24.
-->

---
class: slide-review
---

<header class="slide-header">
  <p class="kicker">Project 01 · Google Business Profile</p>
  <h1>Reduce Reply Work Without Giving Up Control</h1>
</header>

<div class="project-layout">
  <div class="media-slot project-media">
    <MediaFrame
      src="/media/review-system.png"
      alt="Google Business Profile review response system"
      label="Add review assistant screenshot"
      fit="contain"
      aspect="16 / 10"
    />
  </div>
  <div class="project-story">
    <p class="code-caption">// problem → solution → value</p>
    <div class="impact-story">
      <p><span>problem</span>Replying across locations is repetitive, but every response still represents the business.</p>
      <p><span>solution</span>Retrieve the review, draft a response, then keep a person in control of the final reply.</p>
      <p><span>value</span>Less first-draft effort, with judgment, tone, and accountability preserved.</p>
    </div>
    <div class="compact-code-flow" aria-label="Review response workflow">
      <code>retrieve()</code><b>→</b><code>draft()</code><b>→</b><code>review()</code><b>→</b><code>publish()</code>
    </div>
    <div class="project-evidence">
      <p><span>contribution</span>OAuth · review retrieval · filters · AI/edit history</p>
      <p><span>next</span>Approval validation · multi-client workflow</p>
    </div>
  </div>
</div>

<footer class="slide-footer"><span>Carlin Hou · Internship Review</span><span>06</span></footer>

<!--
Timing: 0:55

The first problem was repetitive work with real reputational risk. Replying to many Google reviews takes time, but every reply still speaks for the business. I researched the Google Business Profile API and helped build a prototype that retrieves reviews, creates a draft, and records the response history. The important solution was not simply automatic writing. It was a workflow that keeps human review before publishing, especially for negative or sensitive comments. That can reduce first-draft effort while preserving judgment and accountability. The next step is to validate the approval rules and extend the multi-client workflow.

[Sources]
- User-provided internship brief, accessed 2026-07-24.
-->

---
class: slide-rag
---

<header class="slide-header">
  <p class="kicker">Project 02 · Internal support</p>
  <h1>Turn Scattered Knowledge Into Faster Answers</h1>
</header>

<div class="rag-layout">
  <div class="rag-copy">
    <p class="code-caption">// problem → solution → value</p>
    <div class="impact-story">
      <p><span>problem</span>Useful answers were spread across documents, project notes, and past cases.</p>
      <p><span>solution</span>Search company knowledge first, then answer from the retrieved evidence.</p>
      <p><span>value</span>A faster path to trusted answers, with less repeated searching.</p>
    </div>
    <div class="compact-code-flow" aria-label="Retrieval augmented generation workflow">
      <code>question</code><b>→</b><code>retrieve(evidence)</code><b>→</b><code>answer()</code>
    </div>
    <div class="project-evidence rag-evidence">
      <p><span>contribution</span>Knowledge integration · hybrid retrieval · evaluation</p>
      <p><span>next</span>Tune retrieval with internal-user feedback</p>
    </div>
    <p class="takeaway">Existing team knowledge becomes easier to reuse.</p>
  </div>
  <div class="media-slot project-media">
    <MediaFrame
      src="/media/rag-chatbot.png"
      alt="RAG customer support chatbot"
      label="Add RAG chatbot screenshot"
      fit="contain"
      aspect="4 / 3"
    />
  </div>
</div>

<footer class="slide-footer"><span>Carlin Hou · Internship Review</span><span>07</span></footer>

<!--
Timing: 0:55

The second problem was not missing knowledge. It was that useful answers were spread across documents, project notes, and previous cases, so people had to search repeatedly. The prototype searches company knowledge, retrieves relevant evidence, and then uses that evidence to form an answer. I worked on knowledge integration, semantic and keyword retrieval, and an evaluation interface for quality and latency. The practical value is a faster path to trusted internal answers and a reusable knowledge base. Direct feedback from internal users helped us adjust priorities. Voice, speech-to-text, and text-to-speech remained exploration rather than the finished core workflow.

[Sources]
- User-provided internship brief, accessed 2026-07-24.
-->

---
class: slide-booking
---

<header class="slide-header">
  <p class="kicker">Project 03 · Salon booking · MVP</p>
  <h1>Prevent Booking Conflicts Before They Happen</h1>
</header>

<div class="booking-story">
  <p><span>problem</span>A free time slot can still fail when staff, rooms, or equipment conflict.</p>
  <p><span>solution / MVP</span>Check the booking rules together before suggesting a time.</p>
</div>

<div class="booking-map">
  <div class="constraint constraint-a"><span>service.duration</span><span>employee.skills</span><span>staff.schedule</span><span>multiService[]</span><span>addOns</span></div>
  <div class="media-slot booking-media">
    <MediaFrame
      src="/media/salon-booking.png"
      alt="Salon booking assistant interface"
      label="Add MVP interface screenshot · mock data"
      fit="contain"
      aspect="4 / 3"
    />
  </div>
  <div class="constraint constraint-b"><span>room</span><span>chair</span><span>equipment</span><span>planned.calendar</span><span>planned.notifications</span></div>
</div>

<p class="takeaway">MVP goal: fewer manual checks and less back-and-forth before confirming a booking.</p>
<footer class="slide-footer"><span>Carlin Hou · Internship Review</span><span>08</span></footer>

<!--
Timing: 0:55

The third problem looks simple from the customer side: choose a service and find a time. But an open calendar slot may still be invalid if the right employee, room, chair, or equipment is unavailable, or if several services need to happen in sequence. I focused on the PRD, data model, matching logic, and the rules connecting those constraints. The MVP checks those rules together before proposing a time. Its goal is fewer manual checks, less back-and-forth, and fewer scheduling conflicts. Calendar and notification integrations are planned next steps, not completed features.

[Sources]
- User-provided internship brief, accessed 2026-07-24.
-->

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

<!--
Timing: 1:00

My use of AI changed in three stages. In college, I relied on documentation, sample projects, Stack Overflow, and early AI tools to find patterns and answer narrow questions. During my internship experience in Taiwan, AI became more of a coding partner, but its context was still limited and the results were uneven. In New York, I learned to place AI inside a complete product process. I start from the user need, write a clear specification, break the work into steps, set checks, and review what comes back. Technical experience still matters because I need to understand the code, debug problems, and judge quality. AI makes implementation faster, but it makes direction and judgment more important.

[Sources]
- User-provided internship brief, accessed 2026-07-24.
-->

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

<!--
Timing: 0:55

The biggest change is that the bottleneck moved. Before, much of the effort was writing code and increasing implementation speed. In the AI era, the harder questions come earlier: are we solving the right problem, are the requirements clear, and does the result match what users and the business need? My technical background helps me trace the system, debug AI-generated output, and judge code quality. My startup experience helps me see the same product from the viewpoints of a manager, marketing, customer support, and the customer. That combination helps me connect faster implementation to a shared destination instead of treating speed as the goal.

[Sources]
- User-provided internship brief, accessed 2026-07-24.
-->

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

<!--
Timing: 0:45

When I look back on this summer, what matters most is not only the three AI projects. It is how the team taught me to connect business problems, technical decisions, and feedback. I am very grateful to Lewis, Tania, and the entire Universal Processing team for the trust, guidance, and freedom to experiment. I have really enjoyed working with the team, and I would be excited to continue contributing in a larger capacity beyond this internship. There is still a lot I hope to learn, build, and contribute. Thank you.

[Sources]
- User-provided internship brief, accessed 2026-07-24.
- User-provided photograph, IMG_5994.jpeg, accessed 2026-07-27.
-->
