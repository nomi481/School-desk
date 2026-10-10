# 🎓 School Desk

A free, beautiful daily planner for a **chief proctor and teacher**. Runs entirely in the browser – no server, no sign-up, no build step.

## Features

| Page | What it does |
|------|--------------|
| **Dashboard** | Greeting, live clock, today's classes, top priorities, next exam duty, quick actions |
| **My Tasks** | Tasks with category, priority and due date; overdue tasks are highlighted |
| **Timetable** | Weekly class schedule (Monday–Saturday) |
| **Attendance** | Mark Present / Absent / Late per student, overall attendance %, copy report, download CSV |
| **Proctor Log** | Record discipline and other incidents with severity, search and filter |
| **Exam Duty** | Invigilation days, halls and timings with a "days left" badge |
| **Notes** | Auto-saving notebook |
| **Settings** | Your name and school, backup / restore (JSON), erase data |

Also: dark and light theme, print-friendly pages, mobile friendly, and installable as an app (PWA) that works offline.

## Run it

Just open `index.html` in a browser.

For the install-as-app and offline features, serve it over `http(s)` – for example with GitHub Pages (below) or `python3 -m http.server`.

## Publish on GitHub Pages

1. Create a new repository on GitHub and upload all files from this folder.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/ (root)`, then **Save**.
4. After a minute your app is live at `https://YOUR-USERNAME.github.io/YOUR-REPO/`.

## Your data and privacy

All data is stored in your browser's `localStorage` on your own device. Nothing is sent anywhere.
Because it is stored locally, **download a backup regularly** from *Settings → Download backup*. Use *Restore backup* to move your data to another device.

> Tip: do not put real student data in a public repository. Only the app code is in the repo; your data stays in your browser.

## Project structure

```
index.html            App page
css/style.css         Styles
js/app.js             All app logic
sw.js                 Offline support
manifest.webmanifest  Install-as-app settings
icons/icon.svg        App icon
```

## License

MIT – see [LICENSE](LICENSE).
