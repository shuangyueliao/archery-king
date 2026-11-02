# Archery King — Store Submission Materials

## Short description (CrazyGames / GameDistribution / itch.io)

Hold to draw, drag to aim, release to loose! 10 arrows, drifting wind, and
moving targets. Read the flag, time your power, hit the gold for a bullseye.
Can you grade S?

(143 characters)

## Details

- Genre: Sports / Archery / Casual (aim-and-shoot scoring)
- Controls: Hold (mouse button / touch / Space) to draw — the power bar
  oscillates, release at the green sweet spot for true flight. Drag (or
  arrow keys) to move the crosshair. Release to shoot.
- Features:
  - 10 arrows per round, ring scoring 10/8/6/4/2, off-target = 0
  - Wind drift: waving direction flag plus strength chevrons (1-3); the wind
    pushes your arrow sideways — aim upwind to compensate
  - Power timing: under-drawn arrows drop low, over-drawn arrows fly high
  - Arrows 6-10: the target eases up and down and the wind gets stronger
  - Arrow flight with a camera zoom-in, arrows stick into the target with an
    impact wobble and stay there
  - Per-arrow score breakdown on the results screen, total grade F to S,
    best score and grade saved locally, sound toggle
- Tech: Vanilla JavaScript, Canvas, WebAudio. Single-file HTML5, zero external
  assets (no CDN, images or fonts), works offline once loaded, no tracking.

## Tags

archery, bow, target, sports, precision, casual, wind, single-file

## CrazyGames submission checklist
- [x] Self-contained index.html (SDK loads only on crazygames domains)
- [x] gameplayStart / gameplayStop / loadingStart / loadingStop / happytime events wired
- [x] Responsive (canvas scales to fit viewport, portrait-friendly), keyboard + touch
- [x] No external links inside gameplay, no analytics
- [ ] Cover: cover-16x9.png (1280×720)
- [ ] Screenshots: screenshot-raw.png (1280×800)

## GameDistribution
- Upload archery-king-gd.zip (contains only index.html)
- SDK v2 loader is embedded and activates automatically on
  gamedistribution / gd.games domains

## itch.io
- Upload zip (archery-king-itch.zip), mark "This file is playable in browser",
  entry file: index.html, viewport 480×720, kind: html
- Pricing: $0 (donations optional)
