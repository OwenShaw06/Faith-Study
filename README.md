# Faith Study

A simple checklist and streak counter for the "LDS Faith Study Plan: Zero to Well-Rounded" (256 sessions, 7 phases).
Single-file offline PWA, progress saved in the browser (localStorage).

- `template.html` + `sessions.json` + `build.py` generate `index.html` (`python3 build.py`).
- Streak = consecutive days with at least one completed session; today doesn't break it until the day ends.
- Deploy with GitHub Pages (serve the repo root).
