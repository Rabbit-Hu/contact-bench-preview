# Contact benchmark preview

Static interactive preview of linear shake, rocking shake, snap wedge and wedge force-window experiments.

Open `index.html` in a browser. No build step or simulator installation is needed.
The plots are available immediately; each 3D replay loads on request, with one active at a time.

## Files

- `index.html`: report, plots, summary tables and parameter details.
- `assets/js/`: offline Three.js viewer and Plotly bundles.
- `assets/replays/`: saved geometry, poses and contact data.
- `assets/previews/`: static preview images.
- `assets/licenses/`: bundled library licenses.
- `.nojekyll`: serves the files directly through GitHub Pages.

## GitHub Pages

In Settings → Pages, select Deploy from a branch, `main`, and `/(root)`.
This repository contains only the exported preview; benchmark code and simulation environments are maintained separately.

## Stock-finger pilots

`stock-yam/` contains measured thin-object capture and raised-release pilots using the original YAM/Linear 4310 CAD, with four GPU backends, CPU feasibility, analytical release references and dedicated physics timings. The frictionless-slide pilot is explicitly diagnostic and not promoted. Its `assets/` and `data/` directories contain only browser assets and derived metrics.
