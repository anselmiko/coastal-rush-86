# Coastal Rush '86

A self-contained browser arcade racer inspired by 1980s coastal racing games. Built with HTML5 Canvas and vanilla JavaScript; no dependencies, build tools, or server-side code.

## Run locally
Open `index.html` in a modern browser. For best results, use a local static server or GitHub Pages.

## Publish free with GitHub Pages
1. Create a GitHub repository, for example `coastal-rush-86`.
2. Upload `index.html` and this README to the repository root.
3. Open **Settings → Pages**.
4. Under build/deployment, choose **Deploy from a branch**, select `main` and `/ (root)`, then save.
5. Wait for GitHub Pages to publish the site. The URL will look like `https://YOUR-USERNAME.github.io/coastal-rush-86/`.

## Controls
- Desktop: Left/Right or A/D to steer, Up/W to accelerate, Down/S to brake, P to pause, M to toggle sound.
- Mobile: on-screen steering, brake, and acceleration buttons.
- Pick one of three scenic stages from the title screen.
- Best score is stored locally in the browser on the device.

## Notes
- Sound is synthesized with the Web Audio API and starts after a user gesture (browser autoplay policy).
- This prototype uses original canvas-drawn graphics and generated sound, not copyrighted OutRun assets.
- High scores are stored in localStorage on each device, not shared between players.
- This is a prototype: collision handling and pseudo-3D road rendering are intentionally simple and can be expanded.
