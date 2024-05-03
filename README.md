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

# To-Do
- Actually write some code (lmao)
- Remember to use the GitHib shortcodes
- Fight for justice for the :hamster: emoji (otherwise known as the only animal face emoji unusable with Emoji Kitchen

| Animal Emoji | Compatible? |
| ------------ | ----------- |
| :monkey_face: | :ballot_box_with_check: |
| :lion: | :ballot_box_with_check: |
| :tiger: | :ballot_box_with_check: |
| :cat: | :ballot_box_with_check: |
| :dog: | :ballot_box_with_check: |
| :bear: | :ballot_box_with_check: |
| :polar_bear: | :no_entry_sign: |
| :koala: | :ballot_box_with_check: |
| :panda_face: | :ballot_box_with_check: |
| :hamster: | :no_entry_sign: |
| :mouse: | :ballot_box_with_check: |
| :rabbit: | :ballot_box_with_check: |
| :fox_face: | :ballot_box_with_check: |
| :raccoon: | :ballot_box_with_check: |
| :cow: | :ballot_box_with_check: |
| :pig: | :ballot_box_with_check: |
| :zebra: | :no_entry_sign: |
| :unicorn: | :ballot_box_with_check: |
| :horse: | :no_entry_sign: |
| :frog: | :ballot_box_with_check: |
| :lizard: | :no_entry_sign: |
| :t-rex: | :no_entry_sign: |
| :sauropod: | :no_entry_sign: |
| :turtle: | :ballot_box_with_check: |
| :alligator: | :no_entry_sign: |
| :snake: | :no_entry_sign: |
