# Planning Poker

A tiny planning-poker card deck for your phone: 0, 1, 2, 3, 5, 8, 13, 21.

**Live:** https://k7n4n5t3w4rt.github.io/planning-poker/

## How to use

1. Open the page. It always starts on 0.
2. Swipe sideways to your estimate.
3. When everyone's ready, turn your phone around to reveal.

The screen stays awake while the page is open (where the browser supports the Screen Wake Lock API).

**Install:** use your browser's "Add to Home Screen" (Safari: Share → Add to Home Screen; Chrome: menu → Install app / Add to Home screen). It then opens full-screen like an app.

## Files

- `index.html` — the whole app (inline CSS and a few lines of JS)
- `manifest.webmanifest` — web app manifest for installing
- `icon.svg` — app icon / favicon
- `icons/` — PNG icons (192, 512, maskable 512, 180 apple-touch) and the maskable SVG source
- `.nojekyll` — tells GitHub Pages to serve files as-is

Plain static HTML: no framework, no build step, no dependencies, no service worker, no external requests.

## Run locally

From the repo root:

```bash
python3 -m http.server 8000   # then open http://localhost:8000/
# or
npx serve
```
