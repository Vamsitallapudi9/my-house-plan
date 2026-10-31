# Cellar + 2 BHK home — 26′ × 94′ plot

Interactive plans and 3D models of the house. Static HTML, no build step.

| Page | What it shows |
|---|---|
| [`index.html`](index.html) | Landing page linking everything |
| [`plan-3d.html`](plan-3d.html) | Plot, cellar and 2 BHK plans + 3D model |
| [`2bhk-3d.html`](2bhk-3d.html) | Furnished 2 BHK first floor in 3D |
| [`walkthrough.html`](walkthrough.html) | Walkable tour of the whole property (desktop + mobile) |
| [`plan-2d.html`](plan-2d.html) | 2D dimensioned plot plan |

## Publish with GitHub Pages
1. Create a new public repo on github.com named `my-house-plan`. Leave it empty; this folder has its own README.
2. On the repo page click **Add file → Upload files** (or "uploading an existing file"), drag all 6 files from this folder in, then **Commit changes**.
3. Settings → Pages → Source: **Deploy from a branch** → Branch: `main`, folder `/ (root)` → Save.
The site will be at `https://vamsitallapudi9.github.io/my-house-plan/`.

## View locally
`python3 -m http.server 8765` then open http://localhost:8765/
