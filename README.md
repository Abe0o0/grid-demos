# grid-demos

GitHub Pages host for the grid demo boards (`/hig`, `/packaging`,
`/tools`) and the Villa Paradiso walkthrough (`/villa`).

The three grid pages are **baked artifacts**: `index.html` is rendered
from a single shared UI skeleton plus a per-grid theme and partials, and
`data.js` carries only the 40 demo pins. Do not edit them in place —
they get overwritten on the next bake. Raw pools / call sheets / CSVs
are banned from this repo (see `.gitignore`).
