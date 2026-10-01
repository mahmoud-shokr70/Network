# Network — Facility Operations Documentation

Interactive, self-contained reference for the facility network
(**LPC, Gateway, Sub-gateway, Hub**) across the **Cairo, Giza and Alexandria** zones —
covering inbound receiving, ships-to destinations, each node's role, and status.

## Live site
Once GitHub Pages is enabled, it is served at:

**https://mahmoud-shokr70.github.io/Network/**

## What's in this repo

| File | Purpose |
|------|---------|
| `index.html` | The full documentation page (opens at the site root) |
| `diagram.png` | The network flow diagram as an image |
| `facility_network_documentation.pdf` | One-page PDF spec (linked from the page) |
| `README.md` | This file |

The site is **100% static** — inline CSS, no build step, no external dependencies —
so it runs on GitHub Pages out of the box.

## Enable GitHub Pages (one-time, ~1 min)
1. Open the repo → **Settings** → **Pages** (left menu, under "Code and automation").
2. **Build and deployment** → **Source**: choose **Deploy from a branch**.
3. **Branch**: select **main** · folder **(root) /**.
4. Click **Save**.
5. Wait ~1 minute, then open **https://mahmoud-shokr70.github.io/Network/**

## Updating the site
Replace `index.html` (and/or the PNG/PDF) here and commit — the live page updates automatically.

To regenerate the PDF/PNG from the HTML: open `index.html` in a browser →
*Print → Save as PDF*, or take a screenshot.
