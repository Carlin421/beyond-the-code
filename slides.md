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
class: slide-process
---

<header class="slide-header">
  <p class="kicker">02 / How I work</p>
  <h1>The Work Started Before the Code</h1>
</header>

<div class="process-layout">
  <div>
    <p class="code-caption">// product loop</p>
    <div class="workflow" aria-label="Context to feedback workflow">
      <span>context</span><b>|&gt;</b><span>requirements</span><b>|&gt;</b><span>jira</span><b>|&gt;</b><span>prototype</span><b>|&gt;</b><span>test</span><b>|&gt;</b><span>feedback</span><b>|&gt;</b><span>iterate</span>
    </div>
  </div>
  <div class="media-slot">
    <MediaFrame
      src="/media/jira-workflow.png"
      alt="Jira workflow screenshot"
      label="Add Jira workflow screenshot"
      fit="contain"
      aspect="16 / 10"
    />
  </div>
</div>

<p class="takeaway">Development starts with shared understanding.</p>
<footer class="slide-footer"><span>Carlin Hou · Internship Review</span><span>03</span></footer>

<!--
Timing: 0:45

For me, each project started before the code. I reviewed project descriptions and company knowledge, clarified open requirements, and translated them into Jira tasks. Then I designed and built prototypes, tested them, and showed progress in weekly meetings. One-on-ones with my manager helped me understand the reasoning behind decisions. Sharing work early created business value because the team could correct assumptions before we invested more time. Feedback was not the final step. It became part of every development cycle. That process helped move unclear ideas toward systems the team could evaluate together.

[Sources]
- User-provided internship brief, accessed 2026-07-24.
-->

---
class: slide-projects
---

<header class="slide-header">
  <p class="kicker">03 / The work</p>
  <h1>Three Projects. Three Different Problems.</h1>
</header>

<div class="project-columns">
  <article v-click>
    <span>01</span>
    <div><code>generate()</code><h2>AI Review Assistant</h2></div>
    <p>Content generation with human control.</p>
  </article>
  <article v-click>
    <span>02</span>
    <div><code>retrieve()</code><h2>Internal Support Chatbot</h2></div>
    <p>Trusted retrieval and grounded answers.</p>
  </article>
  <article v-click>
    <span>03 / MVP</span>
    <div><code>coordinate()</code><h2>Salon Booking Assistant</h2></div>
    <p>Business-rule reasoning and resource coordination.</p>
  </article>
</div>

<p class="takeaway project-range">One technology. Three different product responsibilities.</p>
<footer class="slide-footer"><span>Carlin Hou · Internship Review</span><span>04</span></footer>

<!--
Timing: 0:35

These three projects used AI for three different jobs. The review assistant generated content while keeping a person in control. The support chatbot retrieved trusted company knowledge. The salon assistant coordinated several business rules. My contribution was different in each project, from API research and retrieval work to PRD development and data modeling. The salon project is an MVP. It validates the core logic and workflow; it is not a finished production system. The range taught me that AI is not one generic solution. Each product needs a different responsibility, risk model, and definition of success.

[Sources]
- User-provided internship brief, accessed 2026-07-24.
-->

---
class: slide-review
---

<header class="slide-header">
  <p class="kicker">Project 01 · Google Business Profile</p>
  <h1>Human Review Stays in the Reply Workflow</h1>
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
    <p class="code-caption">// designed approval workflow</p>
    <div class="vertical-workflow six-step" aria-label="Review response workflow">
      <span>retrieve()</span><b>→</b><span>generate()</span><b>→</b><span>review()</span><b>→</b><span>edit()</span><b>→</b><span>publish()</span><b>→</b><span>record()</span>
    </div>
    <div class="project-evidence">
      <p><span>contribution</span>OAuth · review retrieval · filters · AI/edit history</p>
      <p><span>next</span>Approval validation · multi-client workflow</p>
    </div>
    <p class="takeaway">Useful automation increases speed<br>without removing accountability.</p>
  </div>
</div>

<footer class="slide-footer"><span>Carlin Hou · Internship Review</span><span>05</span></footer>

<!--
Timing: 0:55

The first project addressed a clear business problem: replying to many Google reviews takes time, but every reply still represents the company. I researched the Google Business Profile API and helped design and implement the prototype workflow around OAuth, business locations, review retrieval, filters, AI drafts, and response history. The key product decision was to keep human review and editing before publishing, especially for negative or sensitive reviews. That creates a path toward faster, more consistent drafts without giving up accountability. The next step is to validate the approval rules and extend the multi-client workflow. Yelp remains only a possible future direction, not a completed or confirmed integration.

[Sources]
- User-provided internship brief, accessed 2026-07-24.
-->

---
class: slide-rag
---

<header class="slide-header">
  <p class="kicker">Project 02 · Internal support</p>
  <h1>The Chatbot Searches Before It Answers</h1>
</header>

<div class="rag-layout">
  <div class="rag-copy">
    <p class="code-caption">// grounded answer + evaluation pipeline</p>
    <div class="rag-pipeline" aria-label="Retrieval augmented generation workflow">
      <span>question</span><b>→</b><span>retrieve(evidence)</span><b>→</b><span>generate(grounded_answer)</span><b>→</b><span>evaluate()</span>
    </div>
    <div class="rag-labels">
      <span>Semantic retrieval</span>
      <span>Keyword retrieval</span>
      <span>Quality + latency evaluation</span>
      <span>Chat + voice workflows</span>
      <span>Speech-to-text · explored</span>
      <span>Text-to-speech · explored</span>
    </div>
    <div class="project-evidence rag-evidence">
      <p><span>contribution</span>Knowledge integration · hybrid retrieval · evaluation</p>
      <p><span>next</span>Tune retrieval with internal-user feedback</p>
    </div>
    <p class="takeaway">The best technical idea is not always<br>the most useful product decision.</p>
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

<footer class="slide-footer"><span>Carlin Hou · Internship Review</span><span>06</span></footer>

<!--
Timing: 0:55

The second project solved a different problem. Useful internal answers already existed, but they were spread across documents, project descriptions, and previous cases. The prototype searched company knowledge, retrieved evidence, and used that evidence to produce a grounded answer. I worked on knowledge integration, semantic and keyword retrieval, and an evaluation interface for answer quality and latency. The business value is faster access to trusted knowledge and less repetitive searching. Because internal users were easy to reach, I could show prototypes and get direct feedback. That feedback changed priorities. Chat and voice workflows, including speech-to-text and text-to-speech, were explored rather than presented as a finished core workflow.

[Sources]
- User-provided internship brief, accessed 2026-07-24.
-->

---
class: slide-booking
---

<header class="slide-header">
  <p class="kicker">Project 03 · Salon booking · MVP</p>
  <h1>The Salon MVP Starts With Business Rules</h1>
</header>

<p class="booking-contribution"><span>contribution</span>PRD · data model · matching rules · system constraints</p>

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

<p class="takeaway">When implementation becomes faster, unclear requirements become more expensive.</p>
<footer class="slide-footer"><span>Carlin Hou · Internship Review</span><span>07</span></footer>

<!--
Timing: 0:55

The salon MVP looks simple from the customer side: choose a service and find a time. But a valid appointment may depend on service duration, employee skills, schedules, rooms, chairs, equipment, add-ons, and several services in sequence. I focused on the PRD, data model, matching logic, and rules that connect those constraints. The potential business value is fewer scheduling conflicts, less manual coordination, and better use of staff and resources. This is still an MVP. Its job is to validate the rules and core booking flow before production work. Calendar and notification integrations are planned next steps, not completed features.

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
<footer class="slide-footer"><span>Carlin Hou · Internship Review</span><span>08</span></footer>

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
<footer class="slide-footer"><span>Carlin Hou · Internship Review</span><span>09</span></footer>

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
    <p class="closing-journey">From military service in Taiwan<br><span>to building AI products in New York.</span></p>
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

When I think back to the interview I completed during military service, I could not have imagined that only a few months later I would be in New York presenting three AI projects I helped build. I am very grateful to Lewis, Tania, and the entire Universal Processing team for the trust, feedback, and freedom to experiment. I have really enjoyed working with the team, and I would be excited to continue contributing in a larger capacity beyond this internship. There is still a lot I hope to learn, build, and contribute. Thank you.

[Sources]
- User-provided internship brief, accessed 2026-07-24.
- User-provided photograph, IMG_5994.jpeg, accessed 2026-07-27.
-->
