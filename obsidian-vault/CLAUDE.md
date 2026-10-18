---
title: "Vault Map"
type: moc
status: evergreen
tags: [notes/system]
created: 2026-05-03
updated: 2026-08-16
---

# Vault Map

The root index. Every live project, learning track and area with its path and a one-line status, plus the conventions the rest of the vault follows. Written to be read by a person at a glance and by an AI assistant without guessing - if a program has to search the tree to find something listed here, this note is out of date. Keep it current after anything is created, moved, archived or changes status.

## 05-Planning

| Note | What it is |
|---|---|
| [[roadmap]] | The plan to the exam in November: the dates, the board (Now, Next, Frozen, Done, Killed, Not now), the sprints and the cap. Read it first for any planning question |
| [[sprint]] | S1, W34-W35 (17 - 30 August): one goal, at most three deliverables, at most two home items, the review at the bottom |
| [[today]] | Today's plan: one main task, at most two others, the Work line, the reminders due |
| [[reminders]] | Dated reminders only |
| `archive/` | Closed plans, one folder per cadence: `daily/`, `sprints/`, `quarters/` |

## 10-Projects - grouped as on the board

| Project | Path | Board | Status |
|---|---|---|---|
| [[recipe-box-app]] | `10-Projects/recipe-box-app/` | Now, build | active - a full week cooked from it by 30 August |
| [[home-backup-plan]] | `10-Projects/home-backup-plan/` | Now, home | active - first copy by 23 August |
| [[balcony-herbs]] | `10-Projects/balcony-herbs/` | Frozen | deferred - back in March |
| [[bike-commute]] | `10-Projects/bike-commute/` | Done | reviewed - a habit now |

## 15-Learning - tracks and courses

| Note | Path | Board | Status |
|---|---|---|---|
| [[learning]] | `15-Learning/learning.md` | hub | evergreen - the tracks in order, and how I learn |
| [[portuguese-a2]] | `15-Learning/portuguese-a2/` | Now, learning | active - exam on 21 November |
| [[portuguese-a2-course]] | `15-Learning/courses/portuguese-a2-course/` | course | active - unit six of ten |
| [[web-basics-course]] | `15-Learning/courses/web-basics-course/` | course | reviewed - done, it built the recipe page |

## 20-Areas

| Area | Path | Status |
|---|---|---|
| [[home-kitchen]] | `20-Areas/home-kitchen.md` | active |
| [[digital-life]] | `20-Areas/digital-life.md` | active |
| [[languages]] | `20-Areas/languages.md` | active |
| [[cycling]] | `20-Areas/cycling.md` | active |
| [[money]] | `20-Areas/money.md` | active |

## 30-Notes

- [[backup-rule-321]] - three copies, two kinds of storage, one somewhere else
- [[bike-maintenance-basics]] - the ten-minute weekly check
- [[frontmatter-conventions]] - the properties every note carries
- [[habit-anchoring]] - why habits attach to something that already happens
- [[meal-planning-basics]] - plan on Saturday, shop once, a fallback meal
- [[note-taking-methods]] - folders, links and tags, and what each one is for
- [[plain-text-files]] - why the vault is plain files
- [[portuguese-pronunciation]] - the sounds that keep tripping me up
- [[scope-cutting]] - deciding early, in writing, what a project will not do
- [[spaced-repetition]] - review intervals, and where they fit
- [[weekly-review-method]] - the fifteen-minute Sunday review
- [[zero-based-budget]] - every euro gets a job before the month starts

## Other folders

- `01-Inbox/` - unprocessed captures, plus parked ideas marked `status: deferred` (the Not now list in [[roadmap]]). Looked at only at sprint reviews.
- `50-Research/` - long comparisons and reports. Frontmatter tracks `distributed` and `connected-to`; not listed one by one here.
- `60-Work/` - [[work-private]]: private, excluded from anything public or indexed. Work tasks run in the work tracker, and the daily plan only carries a Work line.
- `90-Logs/YYYY-MM/` - decisions, conversations and the Sunday reviews, filed by the date in the filename. Not listed one by one here.
- `99-Archive/` - finished or abandoned notes, `status: archived`. Projects keep their folder under `99-Archive/projects/`.
- `00-System/templates/` - one template per note type.

## The board and the cap

- [[roadmap]] is the only list of what is open. Every project and track sits in exactly one group on its board, and the note's status follows the group.
- One build, one home project, one learning track at a time.
- A new project enters the board only by replacing a Now item, at a sprint review. New ideas go to `01-Inbox/` and wait.
- The assistant doesn't open project folders or start builds while the three lanes are full. When asked for something new, it says what that would displace, then does what I decide.

## Conventions

- **Folders are lifecycle, not meaning.** `01-Inbox` → `10-Projects` / `15-Learning` / `20-Areas` / `30-Notes` → `99-Archive`. Reasoning in [[2026-08-12-links-over-folders]]; the learning folder came in with [[2026-08-16-planning-reset]].
- **Links carry meaning.** `[[wikilinks]]` for every internal reference. A note nothing links to is a note nobody will find.
- **Frontmatter carries properties.** `type`, `status`, `tags`, `created` on every note - full reference in [[frontmatter-conventions]].
- **Status is trust.** `inbox → planning → active → reviewed → evergreen`, with `deferred` and `archived` as exits. Status changes; the file doesn't move, except into `99-Archive/` at the very end.
- **Supersede, don't delete.** Outdated reasoning stays, marked in place - see the superseded section in [[digital-life]].
- **Tasks** use `- [ ] thing 📅 YYYY-MM-DD`. **Open issues** go at the bottom of a note behind ⚠️.
- **Filenames** are kebab-case; logs are `YYYY-MM-DD-topic.md` under `90-Logs/YYYY-MM/`.

## Where things go

| If it is… | It goes in | `type` |
|---|---|---|
| A thought I haven't processed | `01-Inbox/` | `fleeting` |
| The plan: the roadmap, the sprint, today, reminders | `05-Planning/` | `plan` |
| Something with an end date | `10-Projects/<name>/` | `project` |
| Something I'm learning, on sessions until a date | `15-Learning/<track>/` | `project` |
| A course I'm working through | `15-Learning/courses/<course>/` | `course` |
| Something I maintain indefinitely | `20-Areas/` | `area` |
| Knowledge I could explain to someone | `30-Notes/` | `topic` |
| A long comparison or report | `50-Research/` | `research` |
| A decision, a conversation or a Sunday review | `90-Logs/YYYY-MM/` | `decision` / `chat-log` |
| Anything finished or abandoned | `99-Archive/` | keeps its type, `status: archived` |

## Commands

| I say | The assistant |
|---|---|
| "plan my day" (`/morning`) | Moves yesterday's [[today]] to `05-Planning/archive/daily/`, reads [[sprint]], [[reminders]] and the Now table of [[roadmap]], and nothing else, then writes today: one main task, at most two others, the Work line, the reminders due |
| "end of day" (`/eod`) | Ticks what got done in [[today]] and adds one line on what moved |
| "weekly review" (`/weekly-review`) | Drafts `90-Logs/YYYY-MM/YYYY-MM-DD-weekly-review.md` from the week's daily plans, ending with the board check. On a sprint's last Sunday it also fills the sprint review and drafts the next sprint from its row in [[roadmap]] |
| "log this" (`/log-chat`) | Saves the conversation's decisions to `90-Logs/YYYY-MM/` and links any related research |
| "inbox this" | Creates `01-Inbox/YYYY-MM-DD-slug.md` from the fleeting template |
| "remind me on [date] about [thing]" | Appends a dated line to [[reminders]] |
