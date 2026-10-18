---
title: "Planning reset - one roadmap, a board and a cap"
type: decision
status: reviewed
tags: [planning/roadmap, notes/system]
created: 2026-08-16
domain: planning
confidence: high
---

# Planning reset - one roadmap, a board and a cap

## Context

The Sunday review that closed [[sprint-2026-W32-W33]] ([[2026-08-16-weekly-review]]) found the same pattern for the second sprint running: two projects moved in parallel, both produced good thinking, neither produced the physical step that makes it real. The plan itself was part of the problem. What was open lived in four places at once: the quarter file, the sprint, a weekly plan and the daily plans, each with its own list, so nothing ever said "these three things and nothing else". The daily plans had grown sections for every part of life, and a task carried five days running had become wallpaper.

The folders had a smaller version of the same problem. The Portuguese course was a project in `10-Projects/` next to things with a build, while its course notes sat in a separate courses folder. A learning track doesn't finish when something ships; it runs on sessions until a date.

## Options considered

**Keep the quarter file, tighten the rules.** Cheapest, and it fixes nothing: the quarter file never said what was *not* open, and the sprint kept inheriting everything.

**One flat backlog list.** Honest about everything, and that is the trouble: a list with no limit is a list where everything is equally open.

**One roadmap with a board and a cap.** A single file says what is open, in which group, and how much may be open at once.

## Decision

The third one. From today:

- **[[roadmap]] is the only list of what is open.** Every project sits in exactly one group on its board - Now, Next, Frozen, Done, Killed or Not now - and the status in the project note follows the board.
- **The cap:** one build, one home project, one learning track at a time. Something new enters only by replacing a Now item, at a sprint review. New ideas wait in `01-Inbox/`.
- **The sprint** has one goal, at most three deliverables and at most two home items. Two weeks, and the review sits at the bottom of the file.
- **Today** is one main task, at most two others, a single Work line and the reminders that are due. No carry counts: yesterday's unchecked items come back only if they are still the right call.
- **Reminders** are dated items only, in [[reminders]].
- **The weekly plan file is gone.** The Sunday review is a log in `90-Logs/`, and the week's fixed shape is one row in the roadmap.
- **Learning gets its own folder.** `15-Learning/` holds the tracks (one folder each, like [[portuguese-a2]]) and the courses under `courses/`, with [[learning]] as the hub. The old courses folder folded into it.
- **The quarter file** is closed early and archived ([[2026-Q3]]); its three outcomes became the three Now items.

## Expected outcome

Each sprint review can name exactly what was open, and the answer is three things. The photo backlog either gets its blocked hour or gets dropped, and no task appears on a daily plan five days running again.

## Revisit

At the S2 review on 2026-09-13, or the first time a sprint goal slips twice.

## Links

- [[roadmap]] · [[sprint]] · [[today]] · [[reminders]]
- [[2026-08-16-weekly-review]] - the review this came out of
- [[2026-08-12-links-over-folders]] - the earlier decision to keep folders shallow
