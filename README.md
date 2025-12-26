# Video-Meme-Maker

A simple, browser-based “video meme maker” built as a series of incremental HTML prototypes (`0` through `17`). Each file is a snapshot of progress so you can compare versions, test ideas quickly, and keep earlier iterations available.

## What’s in this repo

- `video meme maker 0.html` … `video meme maker 17.html`
  - Individual versions/iterations of the app.
- `README.md`
  - Project documentation (this file).
- `LICENSE`
  - Project license.

## Features (varies by version)

Depending on the prototype version you open, the app may include:
- Load a local video in the browser.
- Add meme-style text/captions (e.g., top/bottom or positioned text).
- Basic styling controls (font size, color, outline, alignment, etc.).
- UI/UX experiments across versions.

> Note: Because each HTML file is a separate iteration, not every feature exists in every version.

## Getting started

### Option A: Open directly in a browser
1. Download or clone the repo.
2. Double-click one of the HTML files (recommended: start with the highest number, e.g. `video meme maker 17.html`).

**VS Code:**
- Install the “Live Server” extension
- Right-click the latest HTML file → “Open with Live Server”

## Which file should be used?

- For the “current” version, open the highest-numbered file (usually `video meme maker 17.html`).
- To see how the project evolved, open earlier versions in order (`0 → 17`).

## Project goals

- Keep everything lightweight and beginner-friendly (no build step).
- Explore UI/UX approaches for creating video memes in-browser.
- Preserve iterations for learning and comparison.

## Contributing

Contributions are welcome:
- Bug fixes and UI improvements
- Refactoring (shared CSS/JS) while keeping old prototypes intact
- New features (text presets, draggable captions, templates, etc.)

Suggested workflow:
1. Fork the repo
2. Create a feature branch
3. Commit changes with clear messages
4. Open a pull request

## Roadmap ideas

- Merge the latest prototype into a single `index.html` + `style.css` + `app.js`
- Add draggable/resizable text overlays
- Add templates (classic top/bottom, centered, subtitle style)
- Export (if/when implemented) + quality settings
- Mobile-friendly controls

## License

This project is released under the license in the `LICENSE` file.
