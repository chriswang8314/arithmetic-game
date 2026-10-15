# Arithmetic Game

An offline arithmetic speed drill in the style of Zetamac, built as an installable web app.

**Install on iPhone:** open the GitHub Pages URL in Safari → Share → **Add to Home Screen**. After the first load it runs full-screen and fully offline.

- Addition, subtraction (addition in reverse), multiplication, division (multiplication in reverse) with adjustable ranges
- 30 / 60 / 120 / 300 / 600 second rounds; correct answers auto-advance
- Accuracy mode: press Submit to check; right = +1, wrong = −1 and retry until correct
- All settings are remembered between launches
- History screen with per-settings filter, best, average, and accuracy
- On-screen keypad on touch devices, physical keyboard on desktop (`Esc` quits)
- Best / average / history per settings combination, stored on-device

When changing any file, bump `VERSION` in `sw.js` so installed copies update.

Live at: https://chriswang8314.github.io/arithmetic-game/
