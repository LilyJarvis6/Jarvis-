# Daily Bloom

Lily's workout and meal tracker, as an installable web app (no build step).

- `index.html` – the whole app
- `manifest.webmanifest`, `icons/` – home-screen name and icon
- `sw.js` – offline support
- `netlify.toml` – Netlify settings

Data is saved on each device (localStorage, photos in IndexedDB). Use **Export backup** on the Train tab to keep a copy.

## Deploy
Netlify Drop: drag this folder onto https://app.netlify.com/drop.
From GitHub: New site → this repo → base directory `daily-bloom`, no build command, publish directory `.`.
