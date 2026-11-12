# Contact benchmark preview

Static interactive preview of cube linear and rocking shake, thin-object linear and rocking shake, snap wedge (horizontal + table friction), and snap wedge (vertical) experiments.

Open `index.html` in a browser. No build step or simulator installation is needed.
The plots are available immediately; each 3D replay loads on request, then automatically loops its marked range. One viewer is active at a time; Pause, scrubbing and Unload remain available.

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

## Archived detailed-CAD pilots

`stock-yam/` contains measured thin-object capture and raised-release pilots using the original YAM/Linear 4310 CAD, with four GPU backends, CPU feasibility, analytical release references and dedicated physics timings. The frictionless-slide pilot is explicitly diagnostic and not promoted. Its `assets/` and `data/` directories contain only browser assets and derived metrics.

Both thin-object motions include MJWarp and IPC Tuned accuracy presets alongside Steel Tuned. Geometry, mass, friction coefficients and PD drives are unchanged; numerical contact settings and synchronized physics timings are reported in the page.
