# EF Brand System

Graphics standards for the Ethereum Foundation and its clusters: Protocol, Access Layer and Public Sector.

## Files
- `index.html` – the style guide
- `generator.html` – Pixel Grid Background Generator
- `ef-logo.svg`, `logos/` – Ethereum Foundation and cluster logos used on the site
- `logo-packs/` – downloadable logo packs per cluster (SVG + PNG, primary and secondary, dark and light)
- `gallery/` – reference images
- `deck/` – Access Layer presentation deck pages
- `web/` – website screenshots (Protocol, Public Sector)

## View locally
Open `index.html` in a browser.

## Publish with GitHub Pages
1. Upload everything in this folder to the root of a repository.
2. Settings → Pages → Source: *Deploy from a branch* → `main` / `(root)` → Save.
3. The site is live at `https://<user>.github.io/<repo>/` after a minute.

## Edit
- To change the brand, edit the `BASE` and `PRESETS` objects inside `index.html` (colours, pixel presets, gallery, deck and website lists) and commit.
- Add images to `gallery/` and list them in the cluster's `gallery` array.
- If you change a cluster colour, change it in `generator.html` too (`CLUSTERS` near the top of its script).

## Pixel Grid Background Generator
Open a cluster directly with a hash: `generator.html#protocol`, `#access-layer`, `#public-sector`.
