# Session log

What was decided, what was rejected, and what could not be verified. Newest first.

## 2026-10-18: the demo vault on the current structure, v1.0

### Done

- **15-Learning.** The Portuguese track moved out of `10-Projects/` into `15-Learning/portuguese-a2/` (renamed from `learn-portuguese-a2`), the two courses into `15-Learning/courses/<course>/`, and the learning area became the folder's hub (`15-Learning/learning.md`, with a Tracks table). `40-Courses/` is gone.
- **05-Planning: the board and the cap.** New `roadmap.md` (the dates, the board with Now, Next, Frozen, Done, Killed and Not now, the sprints, the cap, how the system runs) and `reminders.md` (dated items only). `sprint.md` is now S1 in the new shape (one goal, at most three deliverables, at most two home items, the review at the bottom) and `today.md` is one main task, at most two others, a Work line and the reminders due. The quarter file moved to `archive/quarters/`, closed early; `week.md` is gone, its fixed points now a row in the roadmap. Archived sprints follow the `sprint-YYYY-Wxx-Wyy.md` naming.
- **Weekly reviews are logs.** The two reviews moved from `05-Planning/archive/weekly/` to `90-Logs/2026-08/YYYY-MM-DD-weekly-review.md`, and the second one ends with a board check. A new decision log, `2026-08-16-planning-reset.md`, explains the switch inside the demo's own story.
- **Status follows the board.** The backup project went from planning to active (it is a Now item), the frozen herbs project got a "Resume here" block, and the sourdough idea in the inbox is parked as `deferred`. Archived projects keep their folder under `99-Archive/projects/`.
- **Conventions.** `CLAUDE.md` is rewritten as the map of the new structure, with the board, the cap and the commands. Research notes carry `distributed` and `connected-to`; `frontmatter-conventions.md` documents them and the board-to-status rule. Four templates were added (sprint, weekly review, course, research) and the daily plan template follows the new shape; templates stay free of links so they don't show up in the graph.
- **The README** gained a folder table and a paragraph on how the plan works. **Cards 1, 2 and 4** were re-rendered: the folders card shows `15-Learning` instead of `40-Courses` and labels `05-Planning` as the plan, the map card shows the track in `15-Learning/`, and the cover's graph was recomputed from the vault's links with the same force layout, choosing among 40 seeds the layout where no note touches another or the `CLAUDE.md` label. Card 3 rendered byte-identical and is unchanged.
- **Checks:** every wikilink resolves, no two notes share a name, no note is an orphan, no long dashes anywhere. A sweep of the tree and of every blob in the history found no employer traces and no real names besides the published authors cited in source lists.

### Decided

- The demo's three lanes are build, home and learning: the same cap as the real vault, with lanes that fit the made-up owner.
- Old plans keep their old shape. Only their place and their links changed, the way the real vault keeps closed plans.

### Rejected

| What | Why |
|---|---|
| A weekly plan file next to the sprint | The current system has none; the Sunday review is a log and the week's shape is one row in the roadmap |
| Links inside templates | Obsidian's graph would show the templates as linked notes |
| Rewriting the history's author name (the old GitHub handle) | The repo is public; rewriting would need a force push for no gain |

### Not verified

- The vault wasn't opened in the Obsidian app; links were checked by a script that resolves them by file name, the way Obsidian does.

### Open

- `claude-setup/`, `git-setup/` and `obsidian-setup/` are still empty placeholders, and card 4 names Claude skills the repo doesn't ship yet.
- The repo has no licence file.
