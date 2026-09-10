# Looper

A tiny web app for looping YouTube videos. Paste a link, name it, and play it as many times as you want — with adjustable playback speed.

## Features
- Player screen: full-width video, play/pause, restart, next
- Repeat: ∞, 2×, 3×, 5×, 10× or a custom number of plays, with a live play counter
- Speed: 0.25×–2×, kept across loop restarts and video switches
- Library screen: add any YouTube link (watch / youtu.be / shorts / embed) with a name, delete any video
- Your queue, chosen repeat count and speed are saved in the browser (localStorage)

## Deploy on GitHub Pages
1. Create a repository and add these files at its root.
2. Settings → Pages → Source: **Deploy from a branch**, branch `main`, folder `/ (root)`.
3. Open the published URL. `index.html` is fully self-contained — no build step, no dependencies.

## Add to an iPhone home screen
Open the published URL in Safari → Share → **Add to Home Screen**. It launches full-screen with the app title "Looper".

## Files
- `index.html` — the whole app, self-contained (open it directly in any browser)
- `source/Looper.dc.html` — editable source
- `source/support.js` — runtime used by the source file
