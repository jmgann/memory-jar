# Memory Jar PWA V7

This package turns the V5 prototype into a basic Progressive Web App.

## Files

- `index.html` — the app
- `manifest.json` — app name, icon, theme, install settings
- `service-worker.js` — offline caching
- `icons/` — app icons

## Important

A PWA install prompt will not work from a plain `file://` open. You need to host it over HTTPS or run it locally with a small web server.

## Fast local test

From this folder, run:

```bash
python3 -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

## Phone test

Easiest path:

1. Upload this folder to Netlify, Vercel, or GitHub Pages.
2. Open the hosted URL on your phone.
3. On iPhone Safari: Share → Add to Home Screen.
4. On Android Chrome: menu → Install app / Add to Home screen.

## Storage reminder

Memories are still stored locally in the browser/device localStorage. Installing the PWA does not create cloud sync.


## V7 changes
- Softer ritual-focused copy.
- Save action renamed to “Drop it in.”
- Added gentle confirmation after saving.
- Empty states and prompts now feel less like journaling/productivity.
