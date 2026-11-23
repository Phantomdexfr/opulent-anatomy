# 0pulent Anatomy

An interactive 3D human anatomy atlas that runs in the browser and installs on your phone like an app.

Made by **Ankit Shukla**. Contact: phantomdx9@gmail.com

## What it does

- Explore the skeleton, muscles and organs in 3D
- Tap any part to see its name, system, size and description
- Tap a group to highlight every part in it
- Search parts by name
- Focus on one part, or isolate it and hide the rest
- Explode the body apart with a slider
- Switch backgrounds: White Lab (default), Clinical Grey, Midnight and Hologram
- Works offline after the first load

## Numbers

- 962 selectable parts
- 402 muscles and 296 bones
- 9 body systems
- 733 part groups
- about 1.2 million triangles
- 4 background themes

## Install on a phone

The app only opens once it's added to the Home Screen.

**iPhone:** open the site in Safari, tap Share, then Add to Home Screen, then Add. Open it from the Home Screen on Wi-Fi the first time.

**Android:** open the site in Chrome, tap Install app (or the menu, then Add to Home screen).

If you open the link inside Instagram or another in-app browser, the page will ask you to open it in Safari or Chrome first.

## Run it on GitHub Pages

1. Put all the files in the root of a public repo.
2. Go to Settings, then Pages. Set Source to Deploy from a branch, choose main and / (root), then Save.
3. After a minute or two the site is live at `https://YOURUSERNAME.github.io/REPONAME/`.

Add `#dev` to the end of the link to skip the install screen on a computer.

Full steps are in `COPILOT_SETUP.md`.

## Files

| File | What it is |
|---|---|
| `index.html` | The app, including the install screen |
| `atlas.dat` | 3D mesh data (binary, don't edit) |
| `meta.json` | Part names and sizes |
| `three.min.js` | 3D rendering library |
| `sw.js` | Offline support |
| `manifest.webmanifest` | App name and icons |
| `icon-*.png` | App icons |
| `LICENSE` | MIT license |

## Updating

Change the version name in `sw.js` (for example `opulent-anatomy-v1` to `opulent-anatomy-v2`) whenever you push changes. Installed copies only update when that name changes. Close and reopen the app once on the phone.

## License

MIT. See `LICENSE`.
