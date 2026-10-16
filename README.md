# Territory Trails — Starter

A free, offline-first browser prototype for a territory-capture game.

## Run locally
Open `index.html` in a modern browser. For reliable PWA service-worker behavior, serve the folder over HTTPS or localhost.

## Deploy to GitHub Pages
1. Create a public repository.
2. Put `index.html`, `manifest.webmanifest`, `sw.js`, and `assets/` at the repository root.
3. Enable GitHub Pages from the `main` branch and `/ (root)`.
4. Open the published URL once while online, then use the browser menu → Add to Home screen.

## Prototype status
- Playable local solo prototype: movement, trail drawing, closing loops, territory percentage, bots, minimap.
- Offline caching through a service worker when served from HTTPS/localhost.
- This starter does **not yet implement real multiplayer networking** or a native Android APK. Those are the next development milestones; a static GitHub Pages site alone cannot host a multiplayer server.
