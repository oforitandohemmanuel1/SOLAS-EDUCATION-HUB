# SOLAS Ocean–Atmosphere Education Hub

This package is a responsive static website prototype built from the final
`SOLAS_3_0_Final_Master_Inventory.xlsx` inventory.

## Preview locally

Because the resource inventory is loaded from JSON, open the folder with a
small local server rather than double-clicking `index.html`.

### Python
```bash
python3 -m http.server 8000
```
Then open `http://localhost:8000`.

## Deploy

Upload the contents of this folder to GitHub Pages, Netlify, Cloudflare Pages,
or the SOLAS web server. No build step or database is required.

## Files
- `index.html` – complete hub interface
- `assets/styles.css` – responsive SOLAS visual system
- `assets/app.js` – search, filters, detail modal, theme and audience journeys
- `assets/resources.json` – all 145 inventory records
- `assets/solas-logo.svg` – scalable SOLAS-styled logo asset

The downloadable logo materials on the SOLAS site request clear attribution.
Confirm the final logo file and brand specifications with the SOLAS team before
public production deployment.
