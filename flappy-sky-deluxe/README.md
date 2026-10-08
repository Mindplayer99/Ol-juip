# Flappy Sky Deluxe 🐥

An improved, fully offline Flappy Bird-style browser game evolved from the original user-supplied HTML. Runs as **one HTML file** without a framework, API, images, or Internet access.

## Play

Download [index.html](./index.html) and open it in a modern browser.

**Controls:** tap/click/Space/Arrow Up/W to flap; pause (button, P, Escape); day/night (moon/sun button, N); sound (button, M). Game-over restart is available with the on-screen button or Enter/Space.

## What's new

- Animated day/night skies, moon, stars, clouds, parallax mountains, lit windows and redrawn dimensional pipes.
- 120 Hz fixed-step physics simulation, height-adjusted consistent flap impulses, smooth tilt and variable refresh support.
- Gap centers restricted to safe vertical bounds and their displacement limited between consecutive pipes.
- Scoring and circular bird-vs-pipe-cap collision detection; gentler first pipe distance and capped progression.
- Auto-pause when the tab is hidden; play/pause/restart; responsive high-DPI Canvas.
- Best-score compatibility with `flappy_best_v2`, audio toggle, medals and preserved replay mechanics.

## Testing

Tested in automated Chromium mobile-sized viewports (390×844 and 320×640) by actually tapping, pausing, switching modes and navigating obstacles. Restart/game-over also verified at 390×844, 320×568 and 430×932; no browser JavaScript errors observed in those tests. Physical Android touch latency is not measured.

## Original

[Original game source](./original-flappy-bird.html) included for backup.

## References

- [MDN — Optimizing Canvas](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Optimizing_canvas)
- [MDN — requestAnimationFrame](https://developer.mozilla.org/en-US/docs/Web/API/Window/requestAnimationFrame)
- [MDN — Pointer Events](https://developer.mozilla.org/en-US/docs/Web/API/Pointer_events/Using_Pointer_Events)

Sources used for design and practice review, not copied code: [flappy-js](https://github.com/mapuya19/flappy-js), [pyforgedev/flappy-bird](https://github.com/pyforgedev/flappy-bird).
