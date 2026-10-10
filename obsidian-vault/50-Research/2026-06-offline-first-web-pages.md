---
title: "Making a small web page work with no internet"
type: research
status: reviewed
tags: [dev/small-tools, research]
created: 2026-06-28
distributed-to: [recipe-box-app]
---

# Making a small web page work with no internet

The kitchen has bad signal, so [[recipe-box-app]] has to work offline. Three ways to do that, from simplest to most capable.

## Options

**Open the HTML file straight from disk.** Works with no internet by definition. The catch: browsers refuse to let a page opened from disk `fetch()` another local file, so the recipes can't live in a separate JSON file read at runtime.

**Put the data in a script file.** `recipes.js` assigns the list to a variable and is loaded with an ordinary `<script>` tag, which browsers *do* allow from disk. The data stays a plain, hand-editable file — the property that mattered in [[plain-text-files]].

**Service worker / installable web app.** Proper offline caching, works on the phone too — but service workers only run on a secure origin, so it needs hosting. Out of scope per [[2026-07-09-recipe-box-scope]].

## Conclusion

Option two. One HTML file, one data file, both opened from disk, both backed up as ordinary files by [[home-backup-plan]].

## Related

- [[web-basics-course]] — where the problem first showed up
