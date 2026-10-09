# research.md · Where distinctive directions come from (2026-10-09)

Three scans: (1) personal-site galleries (~90 sites read), (2) experimental design libraries (~40 sites), (3) what AI agents produce by default. Condensed here; used to pick v03–v10 and to judge collision risk.

## A. The AI-default look (avoid; this is what ~700 classmate pages will mostly be)
- Mode A "Tailwind SaaS": centered hero + badge pill + two pill buttons + 3 equal cards; indigo/purple gradient text; rounded-2xl cards with icon; stats strip "5+ years"; bento grid; glassmorphism; dark #0a0a0a + one glow; fade-up on everything.
- Mode B "tasteful 2026" (Claude's house style): cream #F4F1EA + near-black + terracotta; oversized serif headline with one italic word; tracked-caps eyebrow labels; 01/02/03 numbering; middle-dot separators; monospace data labels; → on every link; hairline "broadsheet" dividers.
- Style words that collapse to one look: brutalist, magazine/editorial, minimal, dark mode, retro, terminal, cyberpunk, glassmorphism, luxury, playful, **swiss** (Helvetica + red on off-white + 12-col + giant grotesque), bento.
- Fonts agents reach for: Inter, Geist, Space Grotesk, DM Sans, Playfair, Instrument Serif, Fraunces, JetBrains Mono, Space Mono.
- Common portfolio tropes: sticky-left identity + "01. About" nav (Brittany Chiang clones); experience timeline with dots; skill bars; tech-logo marquee; typewriter "I'm a ___"; "Let's work together" giant email footer.

Our own tells so far: v01 and v02 both use mono labels, 01/02 numbering, middle dots and → arrows; v02 is textbook "swiss". Fix with approval later.

## B. What agents almost never produce (opportunity)
Asymmetric/overlapping composition · horizontal scroll, scroll-snap, pinning · real imagery (the person's photo, scans, real screenshots) · dense index/table/archive layouts · extreme type-size jumps · non-rectangular containers · specific concrete copy with real numbers · interaction depth (keyboard nav, progressive disclosure, view toggles, facets) · faithful print systems · serif body text · default link blue as the only colour · real CJK typesetting.

## C. Distinctive, real directions (pass: form is real; screenshots prominent; person legible)
| # | Direction | What it is | Axis | Collision | Examples |
|---|---|---|---|---|---|
| 1 | Project table | A real `<table>`: #, product, what, metric, status, year; row expands inline to screenshot | layout/density | low | aliciadubuis.com, danmachado.com, kenjpena.com |
| 2 | Dated log, newest first | Reverse-chronological entries, date · title · paragraph · 1–2 images; no hero | tone/structure | low | jennywen.ca, edvardscott.com, maximiliankaspar.com |
| 3 | Numbered chapters + figures | Each product a chapter, each screenshot a figure 1.1, 1.2 with caption carrying the metric; TOC rail | tone/audience (technical) | low | samthies.com, makingsoftware.com |
| 4 | Principles as filters | The four principles are facet buttons; clicking highlights the products that embody it | visitor action | low | pentagram.com/work, studiofeixen.ch |
| 5 | Name-letter timeline | Vertical timeline; each anchor is one letter of the name; products hang off years | structure/person | low | jlern.com |
| 6 | Overview ↔ List toggle | Same data rendered as image grid or dense text list; a real control | visitor action | low | oliverdupuy.com, abcdinamo.com/catalogue |
| 7 | Micro → full width | Five thumbnails in one row; click expands one to full width, others shrink | interaction | low | schemamagazine.com |
| 8 | Contact-sheet grid, bio last | Grid of screenshots with one-word labels; bio is one line below the grid | layout | low | felixpeault.com, hervethomas.com |
| 9 | Prose bio with inline links | 3–5 first-person paragraphs; every project is a link in running text; monochrome, colour only from screenshots | tone/mood | low | ped.ro, haydenbleasel.com, rsms.me |
| 10 | Mixed-script name lockup + real CJK typesetting | 陈亦奇 / Jessie Chen set at different sizes; Chinese typeface chosen on purpose | typography | very low | emitakahashi.ca |
| 11 | Pinned identity rail + scrolling dossiers | Left column fixed (person, principles, contact); right scrolls five full-width screenshots | layout | medium (avoid the Chiang spotlight) | codefronts split-screen |
| 12 | One product per viewport, scroll-snap, 01/05 | Five full-bleed panels with counter and progress | layout | medium | guillaumecolombel.fr |
| 13 | Horizontal scroll with snap | One row, counter, progress bar; vertical under 768px | layout | medium | henriheymans.com |
| 14 | Editorial front page, asymmetric spans | Products as features with standfirst/deck/pull-stat; unequal column spans; serif + grotesk | layout | medium | every.to, elenascott.co |
| 15 | Manifesto first, projects as Obj. 01 | 3–5 declarative lines large, then projects as objects with full-width images | tone | low–medium | taradash.me, rauno.me |
| 16 | Live "now" strip | Current courses, this week's reading, last commit, "next available" | content | low | tzovar.as, brianlovin.com |
| 17 | Hover-row image preview index | Hairline rows; hovering floats the screenshot; keyboard focus equivalent; mobile reveals when centred | interaction | medium (Framer presets) | tomsears.me |

## D. Typography/colour systems that read as deliberate, not trendy
Monochrome page, colour only from images · serif body text like a book · default link blue as the only colour · catalogue notation as a system (dates 2026.03.14, refs, counters) · one personal glyph as the only decoration · characterful serif display + plain grotesk body (free stand-ins: Newsreader/Source Serif + IBM Plex Sans/Inter Tight) · uppercase micro-labels with big quiet headings, no gradients.
