# Before / After Builder

A web tool for creating **before/after screenshot comparisons** as PNG images.

Fully vibecoded! Only this README section was written by hand.

---

# Vibecoded README

A single-file web tool for composing **before/after screenshot comparisons** into shareable PNG images. Everything runs in your browser — no server, no build step, no uploads. Just open `index.html`.

## Features

- **Document title** rendered across the top of the export.
- **Multiple sections** ("changes"), each with its own title.
- **Multiple before/after pairs** per section.
- **Per-image captions**.
- **Flexible image input** — click to browse, drag-and-drop, or paste from the clipboard.
  - Drop two images on one slot to fill both _before_ and _after_.
  - Drop images on **+ Add before/after pair** or **+ Add change** to create and fill new pairs/sections in one go (extras spill into additional pairs).
- **Reorder** sections and pairs with ↑ / ↓, and **⇄ Swap** before/after within a pair.
- **Customizable** before/after labels, background color, and export quality (1×–3×).
- **Export options**:
  - Download the whole document as one PNG.
  - **⬇ Each section** — download every section as its own PNG.
  - Per-section **⬇ PNG** button on each header.
- **Auto-save** to session storage (survives reloads) with a **Reset all** button.

## Usage

Open `index.html` in any modern browser, or visit the hosted version if published via GitHub Pages.

## License

MIT
