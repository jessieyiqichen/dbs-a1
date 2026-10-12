# dbs-a1 · 25 versions of one personal landing page

Course assignment: Design, Build, Ship · MPCS 51238 · Assignment 1 "Accelerated Prototyping".
One idea, 25 landing-page versions from wide exploration to a final choice, plus a gallery that tells the story.

## What the page is
Jessie Chen's (陈亦奇) personal landing page. Visitor = a hiring manager for an AI product role.
After reading, the visitor should understand how I think about and ship AI products, then open one case study or send an email.

Starting point: I already have a live personal site (repo jessieyiqichen.github.io, deployed on Vercel; editorial "evidence on paper" style).
This assignment questions whether that form is right. It is one candidate, not the answer.

## Content source (hard rule)
- Every version uses only the copy, numbers, links and images in `content.md`. No invented projects, numbers or placeholder text.
- Cutting, regrouping and changing tone is fine. Adding facts that are not there is not.
- All pages are in English.

## Tech constraints (hard rule)
- Plain HTML + CSS, optional small vanilla JS. No frameworks, no packages, no build step, no external APIs, no data storage.
- Do not propose adding any dependency; I will refuse.
- One directory per version, `vNN/index.html`, fully self-contained styles. No shared CSS (directions must not leak into each other).
- Every version has a link back to the gallery, always written as `<a class="back" href="../">← Gallery</a>`.
- Images are shared from `assets/img/`.

## Gallery
- `index.html` is the gallery: 25 cells, each = thumbnail + direction name + one line on what this version tries or changes + link.
- Three acts: v01–v10 go wide; v11–v18 narrow to two or three lines and combine; v19–v25 converge on one line. (The three-act split is ours; the brief only says go wide, narrow down, converge by v20–v25, and needs 25 distinct pages.)
- End with the final choice and why.

## Judging criteria (from my own reactions to early versions)
1. The form must be real, not a costume. If the page pretends to be something it is not (a ledger, a fake transcript), it reads as a gimmick.
2. The visitor must actually see the projects (real screenshots, prominent) and come away understanding who I am. If a form gets in the way of either, drop it.
3. A familiar format with depth on click beats a novel format with nothing to do.

## Workflow rule (hard)
- Every version is discussed first and built only after Jessie explicitly approves the direction. Propose, wait for a yes, then build. Never start a version on your own, and never rebuild a version without approval.

## Direction rules
- Changing only colors or fonts is not a new version. Every new direction changes at least one axis: layout / audience / mood / era / medium metaphor / visitor action.
- Grow directions out of the five projects' own visual language first (ledger, seat map, transcript, thought threads, cognitive radar, terminal...).
- Act 2 combinations (v11–v18): a combination must change the layout axis of its base version; carry over voice, type, mechanism and material. Swapping one component only (as the first v12 did) reads as the same page.
- Act 2 combinations must also carry one visual device from act 1 (ink, halftone, physical objects, photos), not only structure and voice; without it the page reads plain.
- Act 3 versions (v19–v25) stay on one line, but each must change one meaningful decision (hierarchy, what the first screen shows, how a case opens, how much personal content, mobile layout), named in its gallery note, and the change must be visible on the first or second screen: 25 distinct pages is the requirement. A font or colour change alone is never a version.
- A dropped attempt is recorded in `log.md` and the commit history, not in the gallery. Each gallery note describes only the page now in that slot, checked against that page, and any version number it names points to the page now in that slot. A note may keep the reason for a decision, never the story of a page the reader cannot open.
- After each version: update its gallery cell, then one commit whose message is that gallery line.

## Work log
- `log.md` (Chinese, personal) records what I asked for / what the agent gave / where I pushed back / what I decided myself. Needed for the in-class explanation.
