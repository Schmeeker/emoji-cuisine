# emoji-cuisine
Emoji-combining software, attempting to fix some of the issues with Google's Gboard and their Emoji Kitchen

# Goal
Allow a user to combine any emoji in unicode with any other unicode emoji in (hopefully) an intuitive way.

## Why?
Google's [Emoji Kitchen](https://www.google.com/search?q=emoji+kitchen) ((Twitter)[https://twitter.com/emojikitchen]) offers a very inconsistent experience when used on Google's own keyboard, Gboard, on Android. In addition to Gboard's other "smart features," it allows access to emoji kitchen, but without any indication of whether or not a given emoji is compatible with emoji kitchen. The resulting experience is not only frustrating and confusing, but also quite limiting, as the selection of emojis that google allows for usage in emoji kitchen are bizarre.

For example, the Biting Lips (🫦) and the eye (👁️) emojis are usable in emoji kitchen, but the Lips (👄) and Eyes (👀) emoji are completely unusable, despite all four of the emojis appearing in the same category, and three of them being within 5 in unicode code points of each other (440, 441, and 444).

This is really inconsistent and strange behaviour for seemingly simple combinations, and as such this project aims to allow users to programmatically and procedurally generate emoji combinations with more freedom and consistency.

## Disclaimer
This project has absolutely NOTHING to do with Google, Gboard, Android, or the Emoji Kitchen. All copyrights and trademarks are property of their respective owners. This project also has absolutely NO ill-will towards the aforementioned entities/software tools, and simply exists as a silly project to practice using Git, Python, and various Python libraries.

No licence yet, but I'll probably end up using the BSD two-clause because it's nice and simple
