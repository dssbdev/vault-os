---
title: "Roadmap - to the exam in November"
type: plan
status: active
tags: [planning/roadmap]
created: 2026-08-16
---

# Roadmap - to the exam in November

Written at the Sunday review on 2026-08-16, when the quarter file stopped working ([[2026-08-16-planning-reset]]). It replaces [[2026-Q3]] and is the only list of what is open: every project sits in exactly one group on the board below, and the status in its note follows the board.

## Contents
- [[#The dates]]
- [[#The board]]
- [[#Sprints]]
- [[#The cap]]
- [[#How the system runs]]

## The dates

| Date | What |
|---|---|
| 2026-08-17 | S1 starts |
| 2026-08-30 | [[recipe-box-app]]: a full week cooked from the page |
| 2026-09-13 | [[home-backup-plan]]: a deleted file restored from every copy |
| 2026-10-15 | [[portuguese-a2-course]] finished, all ten units |
| 2026-10-31 | Mock exam with the tutor, timed |
| 2026-11-21 | The A2 exam ([[2026-08-09-exam-date]]) |
| March 2027 | [[balcony-herbs]] comes back |

## The board

### Now - one per lane

| Lane | Item | Done when |
|---|---|---|
| Build | [[recipe-box-app]] | A full week cooked from the page without opening anything else (S1) |
| Home | [[home-backup-plan]] | A file deleted on purpose and restored from each copy (S2) |
| Learning | [[portuguese-a2]] | The exam sat on 21 November (S7) |

### Next, in order

1. Photo library clean-up: the 40 GB of duplicates named in [[home-backup-plan]], and only after the restore test has passed (S3)
2. A weekly conversation group in Portuguese, once the exam is behind me

### Frozen

A "Resume here" block at the top of the note and `status: deferred`. Nothing to think about until the date.

| Item | Comes back |
|---|---|
| [[balcony-herbs]] | March 2027, when planting starts |

### Done - reference only

[[bike-commute]] (a habit now), [[web-basics-course]] (it taught exactly enough to build the recipe page), [[notes-app-migration]].

### Killed

Moved to `99-Archive/projects/`: [[meal-kit-subscription]] (cancelled in May) and [[backup-v0-cloud-folder]] (superseded by [[home-backup-plan]]).

### Not now

Ideas, not projects: everything in `01-Inbox/`, like [[2026-08-15-sourdough-starter]] and [[2026-08-16-nas-question]]. Looked at only at a sprint review, and nothing becomes a project unless it replaces a Now item.

## Sprints

| Sprint | Dates | Goal |
|---|---|---|
| S1 | Aug 17 - 30 (W34-W35) | The recipe page in daily use; two backup copies running |
| S2 | Aug 31 - Sep 13 (W36-W37) | The backup plan closed with the restore test |
| S3 | Sep 14 - 27 (W38-W39) | The photo clean-up started; course unit eight |
| S4 | Sep 28 - Oct 11 (W40-W41) | Course units nine and ten |
| S5 | Oct 12 - 25 (W42-W43) | The course finished; speaking practice twice a week |
| S6 | Oct 26 - Nov 8 (W44-W45) | The mock exam, then the gaps it shows |
| S7 | Nov 9 - 22 (W46-W47) | The exam |

Home items, at most two per sprint, are picked at each sprint review. Cooking, cycling and reading run on their own; the Sunday review only notes them.

## The cap

- One build, one home project, one learning track at a time. Work stays in [[work-private]] and never appears on this board.
- A new project enters the board only by replacing a Now item, at a sprint review. New ideas go to `01-Inbox/` and wait.
- The cap binds the AI assistant too: no new project folders while the three lanes are full.
- Frozen means a "Resume here" block in the note and `status: deferred`, nothing more.
- Done means the checkable state in the "Done when" column, not "finished".
- A busy week shrinks the main task to twenty minutes and nothing else moves. A sprint goal may slip once; a second slip cuts something from this roadmap, it never adds a sprint.

## How the system runs

| Piece | Where | Rule |
|---|---|---|
| Today | [[today]] | One main task and at most two others, a Work line, the reminders that are due |
| Sprint | [[sprint]] | One goal, at most three deliverables, at most two home items, the review at the bottom |
| Sunday review | `90-Logs/YYYY-MM/YYYY-MM-DD-weekly-review.md` | Fifteen minutes after the Sunday shop ([[weekly-review-method]]). Every second Sunday it also closes the sprint and opens the next one from this file |
| Reminders | [[reminders]] | Dated items only |
| The week | this table | Monday, Tuesday and Thursday are the reliable evenings and get the main task; Wednesday and Friday stay light; meals are planned on Saturday and shopped for on Sunday ([[meal-planning-basics]]) |
