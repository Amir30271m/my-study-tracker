# 121-Day Mission Tracker – Android Install Guide

This is a mobile-friendly Progressive Web App (PWA) for your WBPRB preparation routine.

## Included
- Your daily timetable (morning physical, commute audio, office, lunch Bengali, family time, night study)
- Daily study goals and completion ticks
- Weekly subject rotation
- 121 calendar-day mission dates: 24 Nov 2026 – 24 Mar 2027
- Bengali beginner lesson
- Physical running log (distance, time, notes)
- 16-week gradual fitness plan
- Export/import backup
- Offline cache after first successful load

## Important: How to install on Android
This ZIP is the app's web package, not an APK. Android Chrome installs it as an app after it is hosted on a secure HTTPS website.

### Easiest method: GitHub Pages (free)
1. Download and extract `120-day-mission-tracker.zip` on a computer.
2. Sign in to GitHub and create a new public repository, e.g. `my-study-tracker`.
3. Upload `index.html`, `manifest.webmanifest`, `sw.js`, and `icon.svg` to the repository root.
4. Open repository Settings → Pages.
5. Under Build and deployment, choose Deploy from a branch, select `main` and `/ (root)`, then Save.
6. Wait for the published HTTPS URL shown in Pages.
7. On your Android phone, open that URL in Google Chrome.
8. Tap Chrome menu (⋮) → Install app or Add to Home screen → Install.
9. Open the new Mission Tracker icon from your phone's home screen.

### Alternative
You can publish the same four files using another HTTPS static hosting provider. Do not just open `index.html` from the ZIP or `file://`; install/offline features require HTTPS or localhost.

## Your data and privacy
- Progress is stored locally in the browser on that device.
- There is no account or cloud sync.
- Use Progress & Backup → Export backup regularly.
- To move to another phone, open the app there and use Import backup.
- Clearing Chrome site data can erase app progress if you have not exported a backup.

## Editing
The app is a simple static PWA. It can be customized by editing `index.html`.
