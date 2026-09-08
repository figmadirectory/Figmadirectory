# 🎨 Figma Directory

**👉 [Open Figma Directory →](https://figmadirectory.github.io/Figmadirectory/)**

A searchable, live index of all MoveInSync Figma files. Search by file name, feature, page, or screen. Click to jump directly to any frame in Figma.

---

## For Team Members (PMs, Designers, Product)

1. **Click the link above** → Opens the Figma Directory
2. **Search** for what you need (e.g., "leave approval," "desk booking," "kiosk")
3. **Click the file or frame** to open it in Figma
4. **No Figma account needed** — just search and browse

---

## For Maintainers (Setup & Updates)

### Initial Setup
- Use `figma-indexer.html` to index all your Figma files (one-time, ~10 min)
- Export the JSON and upload to this repo
- Enable GitHub Pages (Settings → Pages → Source: main)

### Updating the Directory
When you add new files or want to refresh:
1. Open `figma-indexer.html` locally
2. Paste your Figma API token
3. Paste new file URLs
4. Hit **Index Files** → **Export as JSON**
5. Go to GitHub repo → `figma-directory-data.json` → Edit → Paste new content → Commit
6. Refresh the live site in 30 seconds

---

## Features

✅ Search across files, pages, and screens
✅ Click frames to jump to them in Figma (no copy-pasting URLs)
✅ Filter by module/project
✅ See when files were last updated
✅ No Figma account required for viewers
✅ Free hosting on GitHub
✅ Auto-updates when you re-index

---

## Files in This Repo

- **`index.html`** — The live directory your team uses (renamed from figma-viewer.html)
- **`figma-indexer.html`** — Tool to index and export (for maintainers only)
- **`figma-directory-data.json`** — The indexed data (auto-updated by you)
- **`README.md`** — This file

---

## Questions?

Contact: [Your name/team]
Last updated: [Date]
