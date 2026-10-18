---
title: "Frontmatter Conventions"
type: reference
status: evergreen
tags: [notes/system]
created: 2026-08-12
---

# Frontmatter Conventions

The properties block at the top of every note. Kept small on purpose: five fields that every note has, and a few that only some types use. Decided in [[2026-08-12-links-over-folders]].

## Every note

| Field | What it says | Example |
|---|---|---|
| `title` | Human title, can differ from the filename | `"Cutting Scope"` |
| `type` | What kind of thing this is | `topic`, `project`, `decision` |
| `status` | How much to trust it | `active`, `evergreen`, `archived` |
| `tags` | Cross-cutting properties, nested | `[home/cooking, method/planning]` |
| `created` | ISO date | `2026-08-12` |

## Some types

| Field | Types | Why |
|---|---|---|
| `deadline` | `project` | A project without one is an area in disguise |
| `confidence` | `decision` | How sure I was - high-confidence decisions that turn out wrong are the interesting ones |
| `superseded-by` | anything archived | Points at what replaced it, so the old reasoning stays reachable |
| `sprint-dates` | `plan` (the sprint) | The two-week window |
| `week-dates` | the Sunday review log | The week it covers |
| `distributed`, `connected-to` | `research` | Whether the report's findings have been folded into other notes yet, and which ones |
| `updated` | anything | The last real change, when it matters more than the creation date |

## Status lifecycle

`inbox → planning → active → reviewed → evergreen`, with `deferred` and `archived` as exits. Status moves; the file doesn't - links never break.

A project's status follows its group on the board in [[roadmap]]: Now is `active`, Frozen is `deferred`, Done is `reviewed`, Killed is `archived`. The board decides; the note agrees.

## Related

- [[CLAUDE]] - the vault map that lists these conventions at the top level
- [[plain-text-files]] - why properties in plain files are worth anything
- [[note-taking-methods]] - folders vs links vs tags
