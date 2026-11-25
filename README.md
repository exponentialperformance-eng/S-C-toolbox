# S&C Toolbox

A free, offline-capable strength and conditioning toolbox for use on the gym floor. No build step, no dependencies: plain HTML, CSS and JavaScript.

## Tools
- **Unit converter:** N ⇄ kg ⇄ lb (g = 9.81 or 9.80665) plus a left + right force total
- **1RM calculator:** five formulas averaged, percentage table, send to RPE chart
- **RPE / RIR chart:** loads from an e1RM, tap a cell to copy or add to a note
- **% calculator:** x% of Y, X is what % of Y, % change
- **Timer:** intervals, countdown and stopwatch
- **Metronome:** click mode and 4-phase tempo mode (distinct pitch and vibration per phase)
- **Iso belt squat:** net peak force (kg) and relative strength from body mass, body mass + belt and peak force
- **Notes:** slide-up notepad with one-tap result stamps (saved on the device)

## Iso belt squat maths
- A = body mass, B = body mass + belt, C = peak force (N), D = C ÷ g (kg)
- E = D − B (net peak force, kg)
- F = E ÷ A (relative strength)

## Publish with GitHub Pages
1. Create a new GitHub repository and upload everything in this folder (keep the `icons` folder).
2. Go to **Settings → Pages**, set the source to your main branch (root), and save.
3. Open `https://<your-username>.github.io/<repo-name>/` after a minute or two.

## Install on a phone
- **iPhone (Safari):** Share → Add to Home Screen
- **Android (Chrome):** menu → Install app / Add to Home screen

After the first load it works offline. When you change files, bump `CACHE` in `sw.js` (for example `sc-toolbox-v2`) so devices pick up the update.

## Notes
- Audio needs one tap to start (browser rule). Vibration works on Android only.
- Needs HTTPS (GitHub Pages provides it) for install and offline mode. Opening `index.html` straight from disk still works as a normal page.
