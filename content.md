# content.md · Frozen content (every version may use only the facts here)

Source: the live personal site, index.html as of 2026-09-21. Numbers follow that site; read dates are noted where the site gives them.

## Identity
- Name: Jessie Chen (陈亦奇 Chen Yiqi)
- One line: AI Product · Chicago / Shanghai · Open to Opportunities
- Now: MA in Computational Social Science (economics track), University of Chicago, GPA 4.0, class of 2027
- Before: BSc Economics, The Chinese University of Hong Kong
- Looking for: AI product manager roles (AI products first)
- Stack: product definition · AI engineering · data analysis · full-stack development
- Summary: In the past year I took five AI products from requirements through development to launch, solo. Three of them still run automatically in production every day.
- Claim (current site H1): Product judgment is proven by products that ship.
- How I work, one line: I work from data and evidence. The North Star gets its definition first, every model call is logged, and every number on this site can name its dashboard, its metric and its read date.
- Live versions: all five products have a usable online version.

## Contact
- Email: jessiechenyiqi@outlook.com
- GitHub: https://github.com/jessieyiqichen
- Footer: © 2026 Jessie Chen · Hand-written HTML/CSS, no frameworks, no tracking

## Five projects

### 01 Lecture Companion
- Role line: Real-time lecture AI assistant · solo build · proves: interaction design + metrics system + cost engineering
- Paragraph: The bottleneck for asking questions in class is input friction, not model capability. I compressed a question into one click on a transcript sentence, and used multimodal retrieval to fill in whiteboard and formulas. The North Star is after-class review behavior; cost is managed line by line in a usage ledger.
- Numbers: 63 marks, 59 with zero typing | 3-stage rollout, zero rollbacks | ASR cost cut to one quarter
- Links: case study https://jessieyiqichen.github.io/projects/lecture-companion.html | live demo https://jessieyiqichen.github.io/lc-demo/ | guided walkthrough https://jessieyiqichen.github.io/lecture-companion-walkthrough/
- Image: assets/img/lecture-companion.png

### 02 xhs-threads
- Role line: Recovering the train of thought behind Xiaohongshu bookmarks · solo build · proves: differentiated positioning + AI evaluation system
- Paragraph: Bookmarking is frequent; organizing almost never happens. I turned organizing into zero-label, proactive archiving: the user only saves, the AI threads, annotates and checks. Differentiation came from a survey of four competitor types; output quality is gated by an independent reviewer model.
- Numbers: 11 threads, 63 nodes (as of 2026-09) | 90% of calls on the light tier | ¥0.05–0.10 per item
- Links: case study https://jessieyiqichen.github.io/projects/xhs-threads.html | guided demo https://47.94.34.146:8443/demo | try it https://47.94.34.146:8443/try
- Image: assets/img/xhs-threads.png

### 03 Nous
- Role line: Cognitive-twin message agent · three clients · proves: the full path from research to product
- Paragraph: Other bots learn how you talk; this one learns how you decide. A message agent driven by a nine-dimension cognitive model: it judges whether to reply, drafts in your way, and raises a quality warning when you are about to say yes to something you will not do. Feishu bot + Mac floating assistant + Web, all three in daily production use.
- Numbers: behavior prediction 49→71% | 3 clients live | correction flywheel closed
- Links: case study https://jessieyiqichen.github.io/projects/nous.html | guided demo https://jessieyiqichen.github.io/demos/nous.html | vision sandbox https://web-ten-omega-72.vercel.app/agent
- Image: assets/img/nous.png

### 04 JobPilot
- Role line: AI job-search strategist · solo build · open source · proves: product insight + feature trade-offs + engineering quality
- Paragraph: The job search is blocked by people, not information. Existing tools stop at the behavior layer; JobPilot plugs in a cognitive model and language samples to give personal diagnosis and messaging that sounds like you. All six product trade-offs have a written why.
- Numbers: 349 jobs collected, 37 high-score | 31 CLI commands, 544 tests (as of 2026-09) | CI + read-only live demo
- Links: case study https://jessieyiqichen.github.io/projects/job-pilot.html | live demo https://jobpilot-demo-delta.vercel.app | GitHub https://github.com/jessieyiqichen/job-pilot
- Image: assets/img/job-pilot.png

### 05 MusiClaw
- Role line: Shanghai musical-theatre market data platform · solo build · proves: data product + content operations loop
- Paragraph: Public ticketing data turned into a data product that updates itself daily: seat-map snapshots for 86 shows, cast attribution analysis, four content pipelines, feeding a real data account. The AI's scope of responsibility is fully documented.
- Numbers: 86 shows snapshotted daily | 4 content pipelines | fixed 24h post-publish review
- Links: case study https://jessieyiqichen.github.io/projects/musiclaw.html | dashboard https://jessieyiqichen.github.io/musiclaw-demo/
- Image: assets/img/musiclaw.png

## Four ways of working
1. Pain point before solution. Before building, confirm which layer the bottleneck lives in: for classroom questions it is input friction, not model capability; for bookmark organizing it is the act of "having to start" itself. Get the layer wrong and no feature fixes it.
2. Staged rollout and attribution. Ship in stages, one layer of change per stage, so a problem points at its layer immediately. Multimodal retrieval shipped in three stages, fully merged in two days, zero rollbacks.
3. Define the metric before the number. Pick a North Star that reflects real value: marks reviewed after class, not marks made in class. Daily actives by UV, not PV. Any number that enters a report must name its dashboard, its metric and its read date.
4. Cost is a product parameter. Every model call is logged line by line and routed to a model tier by task. Before cutting cost, a shadow run proves quality holds. Savings are the result of verification, not the goal.

## Contact section copy
Looking for AI product roles. Class of 2027, product manager track, AI products first. To go deeper on any project, or for the full resume, email me.
