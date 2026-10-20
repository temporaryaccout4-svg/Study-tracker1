# StudySprint — 17-day interactive tracker

## Included
- 17 individually planned study days
- Flexible optional date for each plan day (days need not be consecutive)
- Interactive task checkboxes and overall/day progress dashboard
- Edit task descriptions and durations; add/remove tasks
- Local browser saving, JSON export/import backup, restore a day's original plan
- Basic service-worker offline shell for a hosted installation

## Important
The app saves progress in the same browser/device using localStorage. It does not sync to the cloud. Export a backup regularly, especially before clearing browser data or switching devices.

## Open as a webpage
You can open `index.html` in a browser to test the tracker. Browser restrictions mean the home-screen install/offline features generally require hosting over HTTPS.

## Install on Android (free hosting option: GitHub Pages)
1. Sign in to GitHub and create a new public repository, e.g. `studysprint`.
2. Upload `index.html`, `manifest.webmanifest`, and `sw.js` to the repository root.
3. In the repository, open **Settings → Pages** and enable deployment from the `main` branch and `/ (root)`.
4. Wait for GitHub Pages to publish the HTTPS site. Open the published URL in Chrome on Android.
5. In Chrome, tap the three-dot menu and choose **Install app** or **Add to Home screen** (the wording varies). Follow the prompts.
6. Open the installed app and test one checkbox, refresh, and confirm it remains checked.

## Plan note
Study time targets are adjustable. The plan balances school/NEB/CEE practice and includes Biology notes. Household chores are excluded. Short reading is included as a light optional task.
