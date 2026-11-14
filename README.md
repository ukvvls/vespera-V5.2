# VESPERA V5.0 — Liquid Glass Assistant Edition

Standalone VESPERA V5.0 with a refreshed Liquid Glass 3D interface, a blue-on-black glossy 3D app icon, and an interactive local task helper.

## Files
- `index.html`: complete responsive app and interface.
- `manifest.webmanifest`: installable PWA metadata and app icon.
- `sw.js`: offline app-shell cache.
- `icon.svg`: blue-on-black liquid-glass 3D icon.
- `README.md`: project notes.

## Local assistant
The built-in helper supports simple in-app commands without a cloud AI/API:
- Plan today's unfinished tasks.
- Arrange selected tasks (select them in the helper's task picker).
- Show overdue tasks.
- Suggest the next task.
- Count unfinished/completed tasks.
- Add a simple task using `أضف مهمة + اسم المهمة` (or `add task + name`).
- Open the tasks or fitness page.

When arranging tasks, it previews the proposed order first. Applying it moves the selected tasks to the top of the task list; it does not change their dates, durations, completion state, or XP.

## Visual update
- Dark futuristic glass surfaces with soft reflections and layered depth.
- Clearer spacing, headings, cards, form controls, and navigation.
- Floating glass navigation on mobile and refined desktop sidebar.
- Blue/pink accent switching remains available for the app interface.
- The app icon itself remains blue-on-black as requested.
- Reduced-motion accessibility support.

## Existing features retained
- Arabic/English interface.
- Local task tracking, XP and E–S player ranks.
- Ready-made study, home, and personal task library.
- Fitness profile fields, BMI information, exercise library, activity log, and 7-day chart.
- Local storage, JSON backup import/export, no login.

## Run
Open `index.html` in a modern browser. For installation and offline caching, publish the folder to a static HTTPS host such as GitHub Pages.

## Privacy
Data stays in browser local storage. Export a backup before clearing browser data. BMI is informational only and is not used for XP or rank.
