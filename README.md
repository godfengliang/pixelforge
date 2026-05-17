# PixelForge — Pixel Art Animation Editor

Create pixel art and sprite animations entirely in your browser. No signup, no install, no backend — just open and draw.

**Live Demo:** [pixelforge-art.surge.sh](https://pixelforge-art.surge.sh/)

## Features

- **7 drawing tools** — Pen, Eraser, Fill (flood fill), Line, Rectangle, Circle, Color Picker
- **Layer system** — Add/remove layers, toggle visibility, reorder
- **Animation timeline** — Multiple frames, playback, FPS control, onion skinning
- **Sprite sheet export** — Horizontal strip PNG with all frames
- **Undo/Redo** — Full history stack
- **Grid overlay** — Toggleable pixel grid
- **Zoom** — 1x–32x with mouse wheel support
- **Keyboard shortcuts** — B (pen), E (eraser), G (fill), L (line), R (rect), O (circle), I (picker)
- **Color palette** — 24-color preset palette + custom color picker
- **Canvas sizes** — 8×8, 16×16, 32×32, 64×64

## Tech

- Pure Canvas API for drawing and rendering
- Custom flood fill algorithm
- Frame-based animation system
- Sprite sheet composition via offscreen canvas
- Zero dependencies — single HTML file
- Touch support for mobile

## License

MIT
