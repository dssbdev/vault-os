---
title: "Why Plain Text Files"
type: topic
status: evergreen
tags: [notes/system, home/files]
created: 2026-05-11
---

# Why Plain Text Files

## Overview

A plain text file is a file you can open in absolutely anything and still read. No account, no subscription, no particular program. It sounds like a limitation and it is mostly a superpower, because the thing you want from personal notes above all else is that they still open in twenty years.

## Key concepts

**You own the files.** They sit in a folder on a disk you can hold. Nobody can change the terms, raise the price, or shut the service down and give you ninety days to export. This is the whole argument, and everything else is a consequence of it.

**They outlive their apps.** Every notes app you have ever used will eventually be discontinued, acquired, or rewritten into something you dislike. Plain files don't care. When the app goes, you switch apps and your notes are already there — which also means switching costs nothing, which in turn means you never have to defend a bad tool because of what it's holding hostage.

**Everything can read them.** Search tools, scripts, backup programs, and anything you write yourself. A folder of plain files is quietly a database that any program can work with, which is why automating anything on top of it is easy while automating on top of a proprietary app is a permissions negotiation.

**They're tiny.** A decade of daily notes is smaller than one holiday photo. That makes copying, versioning, and offsite backups effectively free — see [[backup-rule-321]], where the cheapest part of the whole plan is the text.

**Markdown adds structure without breaking any of it.** Markdown is plain text with a handful of conventions — `#` for a heading, `-` for a list, `**` for bold. Apps render it nicely; a text editor shows you the symbols and the words, still perfectly readable. You get formatting without giving up the format.

## Practical application

Keep notes as `.md` files in ordinary folders. Put a few facts at the top of each one — what kind of note it is, when it was made, how much you trust it — and suddenly the folder is queryable by anything, including yourself in five years.

The honest cost: no live collaboration, no comment threads, no databases with rollups and formulas. If the work needs several people editing at once, use the tool built for that. For one person's thinking, the trade is a bargain.

## Related

- [[note-taking-methods]] — what to put in the files
- [[digital-life]] — the file habits this sits inside
- [[backup-rule-321]] — why small plain files make backups easy
- [[recipe-box-app]] — a small project built on exactly this reasoning

## Sources

- Common ground in the plain-text-notes community; nothing here is controversial
- Personal experience of migrating between three notes apps and losing formatting each time
