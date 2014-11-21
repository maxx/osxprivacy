---
title: "Spotlight"
bg: black
color: white
fa-icon: lock
---

## Explanation

Spotlight is the OS X's search feature. “When you use Spotlight, your search queries, the Spotlight Suggestions you select, and related usage data will be sent to Apple,” Apple’s “About Spotlight & Privacy” document states. “If you have Location Services on your device turned on, when you make a search query to Spotlight the location of your device at that time will be sent to Apple.”

## Solution

From our friends over at  [fix-macosx](https://github.com/fix-macosx/)!

You must update preferences in *TWO* location in System Preferences:

- Disable "Spotlight Suggestions" and "Bing Web Searches" in System Preferences > Spotlight > Search Results.

- Safari also has a "Spotlight Suggestions" setting that is separate from Spotlight's "Spotlight Suggestions". This uses the same mechanism as Spotlight, and if left enabled, Safari will send a copy of all search queries to Apple.

Alternatively, you can download this [automated script](https://github.com/fix-macosx/fix-macosx/blob/master/fix-macosx.py) from [fix-macosx](https://github.com/fix-macosx/fix-macosx)!

Make sense? Didn't think so!

