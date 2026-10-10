---
title: "Stop deepening the folder tree, use links instead"
type: decision
status: reviewed
tags: [notes/system, learning/methods]
created: 2026-08-12
domain: notes/system
confidence: high
---

# Stop deepening the folder tree, use links instead

## Context

The note about backups genuinely belongs in three places: it's a technical topic, it's part of a project, and it's household admin. I filed it, moved it twice, and then spent a week not finding it. That is the ordinary failure of folders - a note gets exactly one, and real ideas belong to several.

The instinct was to build a deeper tree with a folder for each combination. Stopping to think about it first turned out to be worth more than the fix.

## Options considered

**Deeper folders.** Nest until every note has an obvious home. Fails on arrival: the note that belongs in three places still gets one folder, and now the tree is deep enough that finding anything means remembering which branch I chose months ago.

**Tags for everything, one flat folder.** Solves the many-homes problem, and replaces it with a tag list that grows without limit and drifts - `backup`, `backups`, `data-backup`. Tags need discipline nobody sustains without a schema.

**Shallow folders, links for meaning, frontmatter for properties.** Each tool answers one question and only that question: folders say where a note lives in its lifecycle, links say what it connects to, frontmatter says what kind of thing it is and how much to trust it.

## Decision

The third one. Folders stay shallow and lifecycle-shaped - inbox, planning, projects, areas, notes, logs, archive. Meaning is carried entirely by links. Type, status and dates go in frontmatter at the top of each file.

The backup note lives in the notes folder because that's what it is, and it's *reachable* from the project, the area and two logs because those all link to it. The question "where do I file this" gets a boring answer, and the question "what does this relate to" gets an unlimited one. The reasoning is written up properly in [[note-taking-methods]].

## Expected outcome

Filing decisions stop taking any thought, and finding a note happens by walking a link from somewhere related rather than by remembering a path. The measurable version: no note gets moved between folders again for the sake of findability. If I'm still relocating notes in two months, this was wrong.

Second-order benefit worth noting: frontmatter at the top of every file makes the whole vault searchable by anything that can read a file, since these are plain files ([[plain-text-files]]) rather than an app's private format. Filtering to "topic notes I marked evergreen" becomes a query rather than a memory exercise.

## Revisit

2026-11-01, or sooner if the link graph gets dense enough that I stop being able to see structure in it.

## Links

- [[note-taking-methods]] - the full write-up of folders vs links vs tags
- [[plain-text-files]] - why frontmatter in plain files is worth anything
- [[learning]] - the area that pushed this
