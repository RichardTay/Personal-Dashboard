# Workspace Dashboard

A fast, single-file home page for your personal workflow — with keyboard shortcuts, favorites, JSON import/export, and drag‑and‑drop reordering.  
This repo contains **v6** of the dashboard.

<p align="center">
  <img alt="Workspace Dashboard" src="https://img.shields.io/badge/status-stable-22c55e" />
  <img alt="License" src="https://img.shields.io/badge/license-MIT-0ea5e9" />
  <img alt="HTML" src="https://img.shields.io/badge/made%20with-HTML/CSS/JS-6366f1" />
</p>

## Features
- **Keyboard**: `/` focus, **Enter** open first, **↑/↓** navigate, **1–9** quick open, **S** star, **F** starred‑only.
- **Favorites**: star cards, toggle starred view; persisted via `localStorage`.
- **Search**: instant filtering by title/description/tags.
- **Import/Export**: JSON of your links.
- **Drag & Drop**: reorder within or across categories; order persists per section.
- **Theme & Clock**: theme toggle + live clock.
- **Flat structure**: top-level categories only (no subsections).

## Quick Start
1. Download **`index.html`** (or **`dashboard_v6.html`**) from this repo.
2. Open the file in your browser. That’s it — no server or build step required.
3. Optional: set it as your browser **Start Page** or **New Tab** page.

## GitHub Pages (optional)
Publish it as a website:
- Go to **Settings → Pages**.
- **Source**: “Deploy from a branch” → Branch: **main** / folder: **/** (root).
- After it builds, your dashboard is available at `https://<your-username>.github.io/<repo-name>/`.

## Customize
- Edit cards inside each `<div class="grid" id="grid-...">` section.
- Duplicate any `<a class="card">...</a>` block to add a new link.
- To reset drag‑drop order, clear `localStorage` key: `ws-grid-order-v2` (and `ws-stars` for favorites).

## Project Structure
```
workspace-dashboard/
├─ index.html              # Main entry (GitHub Pages will serve this)
├─ dashboard_v6.html       # Same content, kept for reference
├─ readme_v6.txt           # Short, user-friendly notes
├─ .editorconfig           # Consistent indentation in editors
├─ .gitignore              # Common OS/editor ignores
├─ LICENSE                 # MIT
└─ README.md               # This file
```

## Contributing
PRs welcome for small improvements (typos, accessibility, keyboard support, touch DnD).  
For larger changes, please open an issue first to discuss scope and direction.

## License
MIT © 2025 Charlie
