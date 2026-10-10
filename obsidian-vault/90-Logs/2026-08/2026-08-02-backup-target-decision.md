---
title: "Choosing where the offsite backup copy lives"
type: decision
status: reviewed
tags: [tech/backups, home/files]
created: 2026-08-02
domain: home/files
confidence: high
---

# Choosing where the offsite backup copy lives

## Context

I had been treating a synced cloud folder as a backup for about two years. It isn't - it copies deletions and corruption everywhere within seconds, and protects only against a dead machine. Once that was clear, the whole plan needed replacing, and the first real question was where the offsite copy should live. The rule being applied is in [[backup-rule-321]].

## Options considered

**A second drive kept at home.** Cheap, fast, and completely useless against the things that take a whole flat at once. Fine as the *second* copy, not as the offsite one.

**A drive at a relative's house, swapped every few months.** Genuinely offsite, costs nothing after the drive. But it depends on me remembering to swap it, and between swaps the offsite copy is months stale. Anything depending on my memory has a failure rate I already have data on.

**Cheap cold storage.** By far the lowest monthly cost. The catch is on the way back out: restoring is slow, technical, and often carries a retrieval fee, so I would be reluctant to test it. A backup I avoid testing is a backup I don't know I have.

**A mainstream automatic backup service.** Costs a few times more than cold storage per month. Runs unattended, restores by clicking a file, and can be tested any Sunday afternoon without ceremony.

## Decision

Local external drive as the second copy, mainstream automatic service as the offsite third copy.

The deciding factor wasn't price, it was whether I'd ever test it. The monthly difference between the cheap and the convenient option is small in absolute terms; the difference in how often the restore path gets exercised is enormous. Optimising a backup for storage cost is optimising the wrong end - the expensive moment is the restore, and it happens exactly once, on the worst day.

## Expected outcome

By mid-September: three copies exist, the offsite one runs without me, and I have restored a deleted file from each. If I have not managed a test restore by then, the choice was wrong regardless of what it cost.

## Revisit

2027-02-01, at the same time as the subscription review in [[digital-life]]. If the service has raised prices or I still haven't tested a restore, reopen this.

## Links

- [[home-backup-plan]] - the project executing this
- [[backup-rule-321]] - the rule
- [[digital-life]] - the area, including the superseded sync-is-backup reasoning
