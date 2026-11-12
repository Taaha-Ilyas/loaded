# 🍔 Loaded

**Cook it. Stack it. Get Loaded.** A browser cooking game: you start with a broken-down burger stand on Mill Street, cook every burger by hand, chase glowing rare dishes, win over food critics, and grow it into a restaurant empire.

▶ **Play:** https://taaha-ilyas.github.io/loaded/

## Files
| File | What it is |
|---|---|
| `index.html` | The whole game |
| `manifest.webmanifest` + `sw.js` | Lets it install as an app and work offline |
| `favicon.ico`, `assets/icon*.png`, `assets/icon.svg` | Browser tab and app icons |
| `assets/og-image.png` | The preview image Discord and other apps show when you share the link |
| `assets/logo.svg` | Logo |
| `assets/fredoka.woff2` | Game font (Fredoka, SIL Open Font License) |
| `assets/notes/` | Screenshots used in the in-game patch notes |

## Hosting on GitHub Pages
1. Put everything in this folder at the root of a repo called `loaded`.
2. Settings → Pages → Deploy from branch → `main` / root.
3. If the repo has a different name, change the three `taaha-ilyas.github.io/loaded/` URLs near the top of `index.html` so the Discord preview finds its image.

Saves are stored in the browser (3 slots, plus export/import codes).
