---
title: "Recipe Box - one page for the recipes I actually cook"
type: project
status: active
tags: [home/cooking, dev/small-tools, project/active]
created: 2026-07-09
deadline: 2026-08-30
---

# Recipe Box

A single searchable page holding the thirty-odd recipes I cook on repeat, replacing the current mess: screenshots in the photo app, links in browser bookmarks, a few typed into a notes app, and two on paper stuck to the fridge.

## Goal

Open one page, type "lentil", get the recipe. Works with no internet, because the kitchen has bad signal and I am not going to fight a loading spinner with wet hands. Done when I can cook a full week from it without opening anything else.

## Scope

In: a plain web page that reads one file of recipes, a search box, and a print view. Out: accounts, a server, a phone app, photos, ratings, meal-plan generation, sharing with anyone else. Every one of those is a good idea and every one of them is how this project dies unfinished - see [[2026-07-09-recipe-box-scope]] for the conversation where I talked myself down from all of them.

## Decisions made

**One file instead of a database.** Recipes change a few times a month, not a few times a second. A plain data file I can open and read with my own eyes is easier to fix, easier to back up, and impossible to corrupt in a way I can't repair by hand. Same reasoning as [[plain-text-files]] - the boring format outlives the clever one.

**No photos in version one.** Photos are the single biggest source of size, and I have never once picked a recipe by looking at a picture of my own cooking.

**It gets backed up with everything else,** not separately. It rides along in [[home-backup-plan]] as an ordinary file, which is the whole argument for keeping it as one.

## Tasks

- [x] Collect every recipe into one place, however ugly 📅 2026-08-05
- [x] Decide the file format and write three recipes into it by hand 📅 2026-08-13
- [ ] Build the page: list, search box, single-recipe view 📅 2026-08-21
- [ ] Type in the remaining recipes 📅 2026-08-26
- [ ] Cook a full week from it, note everything that annoys me 📅 2026-08-30

## Related

- [[home-kitchen]] - the area this serves
- [[meal-planning-basics]] - the method the page has to support
- [[2026-07-09-recipe-box-scope]] - where the scope got cut
- [[plain-text-files]] - why it's a file and not an app

⚠️ Twelve recipes only exist as screenshots and have to be retyped by hand. That's the boring hour that will decide whether this ships.
