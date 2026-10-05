# Soccer Rotation Planner

Fair substitutions and goalie turns for youth soccer, with a printable sideline sheet.

**Open it:** https://orlando008.github.io/soccer-scheduler/

## On your phone

1. Open the link above and enter the roster once. It's saved in that phone's browser.
2. Add it to your home screen so it opens like an app. On iPhone, use Safari's Share button, then **Add to Home Screen**. On Android, use Chrome's menu, then **Add to Home screen** (or **Install app**).
3. It works without signal once it has been opened, so open it once before you get to the field.

**Someone doesn't show up:** untick **Here** next to their name, tap **Generate**, and the page scrolls to the new plan. Once a plan is showing, **Someone missing? Change who's here** jumps back to the roster.

## Files

- `index.html`: the whole app (one file, no dependencies). The comment at the top lists how it works.
- `sw.js`: offline cache. Bump `CACHE` when adding files.
- `manifest.webmanifest`, `icon.svg`, `icon-*.png`, `apple-touch-icon.png`: home-screen app details.

## Hosting

GitHub Pages serves the repository root from the `main` branch (Settings, then Pages, then "Deploy from a branch", `main`, `/ (root)`).
