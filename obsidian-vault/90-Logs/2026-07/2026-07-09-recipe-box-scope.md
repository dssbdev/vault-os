---
title: "Cutting the recipe project down to something that ships"
type: chat-log
status: reviewed
tags: [home/cooking, dev/small-tools]
created: 2026-07-09
topic: recipe-box-app scope
chat-type: planning
---

# Cutting the recipe project down to something that ships

## Summary

Talked through what a personal recipe app should be, starting from a feature list I'd been adding to for a month: accounts, photos, star ratings, a shopping-list generator, a phone app, sharing with friends. Went through them one at a time asking what each was actually for. Almost none of them survived that question, and the ones that did were things I could do with a text file.

The version that came out the other side is one page that reads one file and has a search box. That is small enough to finish in a few evenings, which is the only property that matters, because the current alternative is not a worse app — it is screenshots in a photo library.

## Key decisions

- One data file, not a database. Recipes change a few times a month; the simplest thing that can possibly work is genuinely enough here.
- No photos in the first version. I have never chosen a recipe by looking at a picture of it.
- No phone app. The laptop is in the kitchen anyway, and this decision alone removes about eighty percent of the work.
- Done means: I cook a full week using only this page. Not "it's finished", which never arrives.

## Action items

- [x] Write three recipes into the chosen format by hand before building anything 📅 2026-08-13
- [ ] Build the list view before adding search 📅 2026-08-21

## Insights worth keeping

Every rejected feature was designed for a version of me who cooks differently than I actually do — someone who browses for inspiration, cooks new things constantly, and shares them. The real me cooks the same thirty meals and needs to find one of them fast. Scope discipline turned out to be less about ambition and more about being honest regarding who the user is.

The second one: "what is the current alternative?" is a better question than "what would be ideal?" The bar isn't a perfect app, it's a folder of screenshots.

## Links

- [[recipe-box-app]] — the project this scoped
- [[home-kitchen]] — the area it serves
- [[plain-text-files]] — the reasoning behind the one-file decision
