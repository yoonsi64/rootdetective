# Root Detective

A study app for 5th–6th graders learning word parts: affixes, Latin bases and Greek bases.

The app is one file, `index.html`, which works offline with no installs. The icon files beside it are only used for the browser tab and home-screen/desktop icon.

## What's inside

- **Flashcards** for 150 word parts (65 affixes, 43 Latin bases, 42 Greek bases)
- **Daily review** of each student's weakest and least-recent cards
- **Quiz**, **Break it down**, **Build it**, **Match**, **Memory**, **Spell it**, **Word sort** and **Speed round**
- **Context clues**: 3,890 sentences at six challenge levels. After each answer, students see the meaning, a word part clue and a sentence clue. Level 6 (Master) goes up to 8th-grade difficulty and includes 84 touch-and-drop sentences with two mystery words
- **16-week plan** that students unlock one week at a time: after finishing 4 different activities with a week's words, students take its check-in quiz; scoring 8/10 opens the next week. Teachers see every week, and a `#week-5` link opens that week for students
- **Progress history**, detailed statistics and 43 badges
- **Read-aloud**, text size, easier-reading and calm-mode options

## Put it online with GitHub Pages

1. In this repository, go to **Settings → Pages**.
2. Under **Build and deployment**, choose **Deploy from a branch**, branch **main**, folder **/ (root)**, then **Save**.
3. After a minute, the app is live at `https://<your-username>.github.io/rootdetective/`.

To open a specific week, add `#week-5` (or `#weeks-3-4-5`) to the end of the link.

## Add it to a desktop or home screen

The app has its own icon (the detective mascot), so students can open it like an app:

- **Chromebook or Windows/Mac (Chrome or Edge):** open the link, then click the install icon at the right end of the address bar (or **⋮ → Cast, save and share → Install page as app**). Root Detective gets its own window and a desktop/shelf icon.
- **iPad or iPhone (Safari):** tap **Share → Add to Home Screen**.
- **Android (Chrome):** tap **⋮ → Add to Home screen**.

The icon files are `icon.svg`, `icon-192.png`, `icon-512.png`, `icon-maskable-512.png`, `apple-touch-icon.png` and `favicon-32.png`, listed in `manifest.webmanifest`. Keep them next to `index.html`.

## Saving progress

In this standalone version, each student's progress, badges and settings are saved in their own browser on that device.
The class progress report, spreadsheet download and problem reports for the teacher work only in the version hosted on Claude.

## Credits

- Font: URW Gothic © 2013–2015 (URW)++ Design & Development, used under the SIL Open Font License 1.1.
- Context sentences, word breakdowns and some example words were written with Claude and should be checked before classroom use.
