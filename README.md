# Hunter System

A levelling tracker for neurosurgery training: daily and weekly quests, five stats, monthly reading gates, milestone boss fights and ranks from E to S.

It is a standalone web app. It works offline and saves progress on the phone it runs on.

## How it plays

- **Daily:** clear 2 of 3 core quests. Mark a day *On call* (just debrief) or *Post-call* (rest, streak protected). One hidden quest appears each day.
- **Weekly:** clear 7 of the 10 quests. Doing all of them earns Perfect week.
- **Levels:** paced to training. At about 400 XP a week, level 20 takes about 4 months, level 50 about 1.7 years and level 100 about 6 years.
- **Ranks:** need both a level and the real milestones (registrar, paper, MMed, FCS, consultant).
- **Hunter tab:** titles, 3 skill points per level, a class at level 10 (adds a weekly class quest), 18 achievements.
- **Log tab:** weekly report, XP per week chart, 16-week heatmap, personal records.

## Install on iPhone

1. Open the GitHub Pages link in **Safari**.
2. Tap **Share**, then **Add to Home Screen**.
3. Open it from the new Hunter icon. It runs full screen, like an app.

## Backups

Progress is stored on your phone only. Go to **Stats → Copy backup code** every week or two and paste the code into Notes. To move to a new phone, use **Restore from code**.

## Files

- `index.html` — the app
- `sw.js` — offline caching
- `manifest.webmanifest`, `icon-*.png` — Home Screen name and icon
