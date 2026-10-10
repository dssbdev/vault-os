---
title: "The 3-2-1 Backup Rule"
type: topic
status: evergreen
tags: [tech/backups, home/files]
created: 2026-07-21
---

# The 3-2-1 Backup Rule

## Overview

A rule of thumb from professional data storage that works just as well for a shelf of family photos: keep **three** copies of anything you care about, on **two** different kinds of storage, with **one** copy in a different building. Old, unglamorous, and it has outlived every clever alternative.

## Key concepts

**Three copies.** The original plus two backups. Two copies sounds sufficient until you notice that the moment one fails you are down to a single copy, and you will be restoring it under stress. The third copy is not paranoia; it is the margin that lets a failure be an inconvenience.

**Two kinds of storage.** Copies on two hard drives from the same batch tend to fail at similar times, and copies inside one service disappear together if the account is lost. Different kinds of storage fail for different reasons, and that is exactly the property you are buying.

**One copy elsewhere.** Fire, flood, and burglary do not politely take only the laptop. A copy in the same room as the original protects against a broken machine and nothing more. Elsewhere can be a service on the internet, or a drive at a relative's house that you swap every few months - the physical distance is the feature.

**Sync is not backup.** This is the part that catches most people. A synced folder faithfully reproduces whatever you do, including deletion and corruption, on every device within seconds. It protects against a dead machine, and against nothing else. A backup is different in one specific way: it remembers what the file looked like *before*.

**An untested backup is a rumour.** Backup systems fail silently - a disconnected drive, an expired login, a job that has been erroring for eight months. The only way to know is to delete something on purpose and put it back. Do that on a schedule, not once at setup.

## Practical application

Decide what actually matters first; trying to back up everything is how people end up backing up nothing. For most households it's photos, documents, and anything they made themselves.

Then: original on the machine, second copy on an external drive kept at home, third copy offsite and automatic. Automatic matters more than any technical detail - a backup that depends on remembering is a backup that stops the first busy week.

## Related

- [[home-backup-plan]] - this rule, applied, with dates
- [[digital-life]] - the area it belongs to
- [[plain-text-files]] - small plain files make all of this cheap

## Sources

- Long-standing storage-industry guidance, repeated in essentially every serious backup guide
- The superseded cloud-sync reasoning in [[digital-life]], which is what made the distinction land
