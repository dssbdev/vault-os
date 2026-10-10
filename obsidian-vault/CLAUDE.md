---
title: "Vault Map"
type: moc
status: evergreen
tags: [notes/system]
created: 2026-05-03
updated: 2026-08-17
---

# Vault Map

The root index. Every live project and area with its path and a one-line status, plus the conventions the rest of the vault follows. Written to be read by a person at a glance and by an AI assistant without guessing - if a program has to search the tree to find something listed here, this note is out of date.

## Projects

| Project | Path | Status |
|---|---|---|
| [[recipe-box-app]] | `10-Projects/recipe-box-app/` | active - list view is the next step |
| [[home-backup-plan]] | `10-Projects/home-backup-plan/` | planning - drive not ordered yet |
| [[learn-portuguese-a2]] | `10-Projects/learn-portuguese-a2/` | active - exam booked for November |
| [[balcony-herbs]] | `10-Projects/balcony-herbs/` | deferred to spring |
| [[bike-commute]] | `10-Projects/bike-commute/` | reviewed - done, now a habit |

## Areas

| Area | Path | Status |
|---|---|---|
| [[home-kitchen]] | `20-Areas/home-kitchen.md` | active |
| [[digital-life]] | `20-Areas/digital-life.md` | active |
| [[learning]] | `20-Areas/learning.md` | evergreen |
| [[languages]] | `20-Areas/languages.md` | active |
| [[cycling]] | `20-Areas/cycling.md` | active |
| [[money]] | `20-Areas/money.md` | active |
| [[work-private]] | `60-Work/` | private - excluded from anything public or indexed |

## Planning

[[today]] · [[week]] · [[sprint]] · [[2026-Q3]] - archives live under `05-Planning/archive/`, one folder per cadence.

## Conventions

- **Folders are lifecycle, not meaning.** `01-Inbox` → `10-Projects` / `20-Areas` / `30-Notes` → `99-Archive`. Reasoning in [[2026-08-12-links-over-folders]].
- **Links carry meaning.** `[[wikilinks]]` for every internal reference. A note nothing links to is a note nobody will find.
- **Frontmatter carries properties.** `type`, `status`, `tags`, `created` on every note - full reference in [[frontmatter-conventions]].
- **Status is trust.** `inbox → planning → active → reviewed → evergreen`, with `deferred` and `archived` as exits. Status changes; the file doesn't move.
- **Supersede, don't delete.** Outdated reasoning stays, marked in place - see the superseded section in [[digital-life]].
- **Tasks** use `- [ ] thing 📅 YYYY-MM-DD`. **Open issues** go at the bottom of a note behind ⚠️.
- **Filenames** are kebab-case; logs are `YYYY-MM-DD-topic.md` under `90-Logs/YYYY-MM/`.

## Where things go

| If it is… | It goes in | `type` |
|---|---|---|
| A thought I haven't processed | `01-Inbox/` | `fleeting` |
| Something with an end date | `10-Projects/<name>/` | `project` |
| Something I maintain indefinitely | `20-Areas/` | `area` |
| Knowledge I could explain to someone | `30-Notes/` | `topic` |
| A course I'm working through | `40-Courses/` | `course` |
| A long comparison or report | `50-Research/` | `research` |
| A decision or a conversation worth keeping | `90-Logs/YYYY-MM/` | `decision` / `chat-log` |
| Anything finished or abandoned | `99-Archive/` | keeps its type, `status: archived` |
