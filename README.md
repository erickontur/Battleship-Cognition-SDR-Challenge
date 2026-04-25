# Battleship — You vs AI

A vanilla HTML/CSS/JS Battleship game. Place your fleet, then sink the AI's ships before it sinks yours.

**Play it live:** https://erickontur.github.io/Battleship-Cognition-SDR-Challenge/
## Features
- 10×10 grid, classic 5-ship fleet (Carrier, Battleship, Cruiser, Submarine, Destroyer)
- Manual placement with rotation (press R), or one-click Auto-place
- Hunt-and-target AI with checkerboard parity hunting and line extension on multi-hit ships
- Hit / miss / sunk visuals, ship counts, and a Play Again reset

## Run locally
No build step, no dependencies. Either:

- Open `index.html` directly in your browser, **or**
- Run a local server (recommended for clean URLs):
  ```bash
  python3 -m http.server 8000
  # then open http://localhost:8000
  ```

## Files
- `index.html` — markup
- `styles.css` — dark naval theme
- `game.js` — game state, placement, firing logic, AI

## License
MIT
