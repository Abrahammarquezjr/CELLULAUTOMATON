# CELLULAUTOMATON
CELLULAUTOMATON is a generative art tool that runs an infinite, self-evolving visual simulation directly in your browser.
**CELLULAUTOMATON** is a generative art tool that runs an infinite, self-evolving visual simulation directly in your browser.

At its core it uses a **cellular automaton** — the same mathematical system behind Conway's Game of Life — where a grid of cells live or die each generation based on how many neighbors surround them. The rule set is seeded randomly, so every run produces a completely unique pattern that grows, blooms, collapses, and reseeds itself automatically forever.

What makes it visually distinctive is the **psychedelic rendering layer** on top. Instead of simple black and white cells, each live cell is colored using a continuously cycling hue that shifts based on three things simultaneously — a global color wave that rolls across the entire canvas over time, a radial ripple that radiates outward from the center like a pond, and the density of each cell's immediate neighborhood. Dead cells bordering live ones emit a soft atmospheric bloom glow. The result looks closer to a living fluid or organism than a math simulation.

**The three controls:**

- **RESET** — kills the current pattern and seeds a brand new one with a random rule and random starting hue
- **RANDOM HUE** — instantly jumps the color cycle to a different point in the spectrum, completely transforming the palette without touching the pattern
- **SAVE PNG** — captures the current frame as a full resolution image you can download
- **Speed slider** — controls how fast generations advance, from meditative slow to rapid flicker

It runs continuously and never pauses — when a pattern dies out or runs for too long it automatically reseeds itself, so it works equally well as a screensaver, a gallery piece, or a tool for capturing generative art stills.

<img width="933" height="674" alt="Screen Shot 2026-02-19 at 4 20 26 PM" src="https://github.com/user-attachments/assets/c0f699ca-a785-4a34-be3b-b8bfe1e905f7" />

<img width="921" height="677" alt="Screen Shot 2026-02-19 at 4 20 17 PM" src="https://github.com/user-attachments/assets/0a19dcd3-62f9-49a3-a562-a902fb4a501b" />

