# Sunny Tracker ☀️🩷

A small, pretty personal tracker for daily exercise, healthy eating and cutting sugar — with streaks, charts and a calendar. It's a single web page that saves everything **on your own device** (no account, no server, works offline), and installs to your phone's home screen like a normal app.

## Files

| File | What it is |
| --- | --- |
| `index.html` | The whole app — screens, styling and logic in one file. |
| `manifest.webmanifest` | Makes it installable (name, icon, colours). |
| `sw.js` | Service worker — lets the app open offline. |
| `icon.svg`, `icon-192.png`, `icon-512.png`, `icon-180.png` | App icons. |

## Run it on your phone (free hosting with GitHub Pages)

1. Go to this repository on GitHub → **Settings** → **Pages** (left sidebar).
2. Under **Build and deployment → Source**, choose **Deploy from a branch**.
3. Pick the branch this app is on and the **/ (root)** folder, then **Save**.
4. Wait a minute, refresh the page — GitHub shows a link like
   `https://<your-username>.github.io/discipline-/`
5. Open that link on your phone, then **Add to Home Screen** (Share menu on iPhone; the ⋮ menu on Android).

Your data lives in the browser on each device. Use **Settings → Copy backup / Save file** now and then so you never lose your history.

## Notes

- Everything is private to your device; nothing is uploaded anywhere.
- Daily reminders work best on Android. On iPhone, a repeating phone alarm is the reliable backup.
- Design language lives in the companion **Sunny Tracker System** design system.
