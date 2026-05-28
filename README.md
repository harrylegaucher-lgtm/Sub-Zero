# Sub-Zero — Mind Map

A standalone mind map builder with two modes: **Build** and **Memorize**.  
No server, no dependencies — single HTML file.

---

## Features

- **Build mode** — create mind maps with unlimited branches, drag nodes, rename by double-clicking
- **Memorize mode** — all non-root nodes become blanks; pick words from the sidebar and place them
- Zoom & pan like Google Maps (scroll wheel, pinch, drag)
- **Levels** — load saved maps directly from any GitHub repo's `levels/` folder
- Export / Import as `.json`

---

## Using Levels

1. Create a repo (public) — for example `yourname/SubZero-Levels`
2. Add a folder called `levels/` at the root
3. Put your exported `.json` mind map files inside it
4. In Sub-Zero, click **📚 Levels**, enter `yourname/SubZero-Levels`, click **Charger**
5. Click any level to load it instantly

### Repo structure

```
SubZero-Levels/
└── levels/
    ├── biologie-cellule.json
    ├── systeme-nerveux.json
    └── immunologie.json
```

### Saving a map as a level

1. Build your map in Sub-Zero (Build mode)
2. Click **💾 Exporter** — saves a `.json` file
3. Move that file into your repo's `levels/` folder
4. Push to GitHub — it appears in the Levels list immediately

---

## Keyboard Shortcuts

| Key | Action |
|-----|--------|
| Double-click canvas | Create root node |
| Double-click node | Edit text |
| `Tab` | Add child to selected node |
| `Delete` / `Backspace` | Delete selected node |
| `Escape` | Deselect |
| `Ctrl+S` | Export |
| `Ctrl+0` | Center view |
| `Ctrl+` `+` / `-` | Zoom in / out |

---

## Files

| File | Description |
|------|-------------|
| `index.html` | The entire app — open this in any browser |
| `levels/` | Put your `.json` mind map saves here |
| `README.md` | This file |

---

## Getting Started

```bash
git clone https://github.com/yourname/SubZero
open index.html
```

Or just download `index.html` and open it directly — no install needed.
