# Territory Trails — Web Prototype

## Files
- `index.html`: game and UI
- `manifest.webmanifest`: installable PWA metadata
- `sw.js`: offline cache

## Publish to GitHub Pages
Upload these files to the repository root. In Settings → Pages, choose Deploy from branch, `main`, and `/ (root)`. Open the HTTPS URL once online, wait for the first load, then use the browser menu → Add to Home screen.

## Current honest status
This is a browser prototype with smooth delta-time movement, joystick/keyboard input, local practice bots, a grid-based map, trail drawing, loop-based area fill, minimap, timer, and offline caching. It is not yet a production-final game: bots are simple, two modes are UI previews, and multiplayer networking plus native Android APK packaging are not included. A static GitHub Pages site cannot by itself provide multiplayer coordination; LAN play needs a separate networking implementation.
