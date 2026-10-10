---
title: "Offsite backup options — compared"
type: research
status: reviewed
tags: [tech/backups, research]
created: 2026-07-24
distributed-to: [home-backup-plan, 2026-07-21-backup-target-decision, backup-rule-321]
---

# Offsite backup options — compared

The comparison behind [[2026-07-21-backup-target-decision]]. Categories, not brands — brands change their prices every year; the trade-offs between categories don't.

## The options

| Option | Monthly cost | Runs unattended | Restore effort | Protects against |
|---|---|---|---|---|
| Synced cloud folder | low | yes | trivial | dead laptop only |
| Drive at a relative's | none after purchase | no — manual swap | drive there and back | everything, but months stale |
| Cold archive storage | lowest | yes | slow, technical, fees | everything |
| Automatic backup service | moderate | yes | click a file | everything, with version history |

## What the table hides

**Sync is in the table to be rejected.** It copies deletions and corruption everywhere — see the superseded section of [[digital-life]] and [[backup-v0-cloud-folder]].

**Restore effort is the real cost.** A backup that's annoying to restore never gets tested, and an untested backup is a rumour ([[backup-rule-321]]).

## Conclusion

Automatic service for the offsite copy, external drive at home for the second. Carried into [[home-backup-plan]].
