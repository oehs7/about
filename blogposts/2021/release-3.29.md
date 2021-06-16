---
title: "Sourcegraph 3.29 release"
publishDate: 2021-06-18T10:00-07:00
description: "The Sourcegraph 3.29 release includes."
tags: [blog, release]
slug: "release/3.29"
published: false
changelogItems:

---

Sourcegraph 3.29 is now available! For this release, we added

## Search results ranking
Star count import from github.com/sourcegraph/ghdump is done. We now have 418321 repos with star data in the production repo table.
Suggestions and search results are now ranked by descending star count on sourcegraph.com (and customer instances if repos there have stars). Try it out live!

## One-click Code Insights creation from your search
TODO IMG PLACEHOLDER
You can now create code insights with 1 click, right from the search query view. Take your search query and turn it into a visualization of your results count in your code over time, to see if your usage of an API, function, or other target is growing or shrinking.

## Improved creation forms for Code Insights
TODO IMG PLACEHOLDER
We now autosuggest and autocomplete the repository field in the correct format. The forms also now autosave your configuration, in case you navigate away before you hit "create." (You can clear your existing autosave if you want to start fresh, with the "clear all fields" button.)

## Batch Changes

### New bulk actions: retry and merge (experimental)

Last release we introduced [bulk actions](https://about.sourcegraph.com/blog/release/3.28/#Batch-changes), allowing users to comment on hundreds of changesets in a few clicks. We add two more bulk actions in this release: retry errored changesets and merge.

Merge is released as an experimental feature. It supports merge commit and squash merge on GitHub and GitLab, and merge commit on Bitbucket. Try it out! For example, you can now filter all changesets that have passed checks and review, and merge them all in a few clicks. [Read more]() TODO.

TODO: video
