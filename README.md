# Prompt Palette — Flux & SDXL Prompt Builder (Frontend)

A lightweight, **offline** HTML tool for assembling prompts for **Flux** (natural language) and **SDXL** (tag-style). Pick a section, click to add items, reorder as pills, and **Copy Prompt**.

- **Mode-aware:** shows only Flux *or* only SDXL phrasing
- **Single-section browsing:** focused Section dropdown
- **Click-to-add + reorder:** ↑/↓ to arrange, × to remove
- **Separator control:** default `, `; customize as you like
- **One-click copy:** paste into ComfyUI, A1111, Invoke, etc.
- **Zero dependencies:** pure HTML/JS; works fully offline

## Quick Start
1. Open `frontend/index.html` in a modern browser.
2. Choose **Mode** (Flux or SDXL) and a **Section**.
3. (Optional) use **Search** to filter items.
4. Click entries to add → reorder in **Selected** → **Copy Prompt**.

## Customize the Library
The library is embedded in `index.html` (as a JSON object). To update it, open the file, find `const LIB = …`, replace with your data, and refresh.

## Project Links
- GitHub: https://github.com/scoilt/prompt-palette-frontend

## License
MIT © 2025 Scoilt
See [LICENSE](./LICENSE).
