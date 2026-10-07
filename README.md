# INVAR Landing

Marketing landing page for INVAR, inside-out analytics for product-led companies.

Recreated from the Claude Design canvas "INVAR Landing Page"
(https://claude.ai/artifact/75qDM5sgEq7HED8Dbfqnwc), artboard `Tabs.dc.html`
("INVAR landing page (tabbed)"), the canvas's launch artboard as of 2026-10-07.

Tabs: Overview, How it works, AskRight, Insights (with a Growth / Product /
CS and Support / Engineering lens switcher), Trust, Pilot.

## Files

- `index.html` — the page. Same source as the artboard, plus a viewport meta,
  description and favicon.
- `support.js` — the DC (Design Component) runtime from the canvas. It bundles
  React, transpiles the inline `<script type="text/x-dc">` component in
  `index.html`, and mounts the page. No build step.
- `invar-mark.svg` — favicon (copied from `invar_product/`).

## Run locally

The runtime needs to be served over HTTP (not opened as `file://`):

    python3 -m http.server 8000

then open http://localhost:8000.
# invar_landing
