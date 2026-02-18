# Boston Crime Heatmap (Leaflet/Folium)

This repository contains an interactive **crime-density heatmap for Boston** generated from an **XLSX spreadsheet of Boston crime statistics** and exported as a standalone HTML map.

The map is built on **Leaflet** with an **OpenStreetMap** baselayer and a **heat layer** of incident coordinates, centered on Boston (approx. `42.3601, -71.0589`) at zoom level ~12. :contentReference[oaicite:0]{index=0}

---

## What’s in this repo

- **`Boston-Crime-Heatmap.html`** — the interactive heatmap you can open in any modern browser. :contentReference[oaicite:1]{index=1}

---

## How to view the heatmap

### Option A — Open directly
1. Download / clone the repo
2. Double-click `Boston-Crime-Heatmap.html`
3. The map will open in your default browser

### Option B — Serve locally (recommended)
Some browsers restrict local file access. If tiles don’t load, run a simple local server:

```bash
# From the repo folder
python -m http.server 8000
