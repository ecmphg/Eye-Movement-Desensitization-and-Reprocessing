# Bilateral Light Visualizer — Mobile + Desktop

## Phone controls
- Single tap the light area: play / pause
- Double tap the light area: fullscreen when the browser supports it
- Swipe down: hide the control panel off screen
- Swipe up: bring the control panel back

## Desktop controls
- Space: play / pause
- F: fullscreen
- H: hide / show controls

## Recording
Video mode records the moving light and can optionally include microphone audio and a front-camera picture-in-picture.
Audio mode records microphone audio while the light continues running.

Recordings are generated locally in the browser and are not uploaded by this site.

Camera/microphone permissions require HTTPS. GitHub Pages supplies HTTPS automatically.

Browser support varies. Some mobile browsers restrict fullscreen, MediaRecorder, or canvas recording. If true fullscreen is unavailable, the page falls back to hiding the controls.

## GitHub Pages
1. Create a public repository, e.g. `bilateral-light`.
2. Upload `index.html`, `.nojekyll`, and `README.md` to the repository root.
3. Go to Settings → Pages.
4. Source: Deploy from a branch.
5. Branch: main.
6. Folder: /(root).
7. Save.

Your URL will normally be:
`https://YOUR-USERNAME.github.io/bilateral-light/`

## Important
This is a visual bilateral-stimulation tool. It should not be represented as independently providing EMDR psychotherapy or as a replacement for care from a qualified mental-health professional.
