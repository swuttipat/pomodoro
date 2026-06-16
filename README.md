# Pomodoro Focus

A mobile-first Pomodoro timer PWA with on-device history tracking.

- **Timer** — focus / short break / long break cycle, configurable durations, progress ring, session labels, sound + vibration alerts, auto-advance.
- **History** — today / this-week totals, focus-minutes bar chart (7 / 14 / 30 days), current streak, best day, and a full session log.
- **Settings** — durations, cycle length, auto-start, sound, vibration, JSON export, clear history.
- **Offline** — installable PWA; all data stored locally on the device (localStorage).

Pure HTML/CSS/JS — no build step, no dependencies.

## Run locally
Serve the folder over http (a service worker needs http/https, not `file://`):

```
python -m http.server 8000
```

Then open `http://localhost:8000`.

## Deploy
Hosted as a static site on GitHub Pages. Any static host works.
