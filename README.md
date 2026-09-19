# Virginia Specialized License Plates

An unofficial, single-page browser for Virginia's specialized license plates. Search, filter, and sort all **341 designs** in one place, with no pagination. Data courtesy of the [Virginia DMV](https://www.dmv.virginia.gov/vehicles/license-plates/search).

## Why

The official DMV site splits the 341 specialized plates across **35 pages**, showing only 10 at a time. This project consolidates every plate onto a single page so you can search, filter, and compare them all at once.

## Features

- **All 341 plates on one page** — no pagination, just scroll
- **Live search** by plate name
- **Category filter** — Special Interest (138), College (96), Military (64), Other (43)
- **Detail filters:**
  - Plate fee — Free ($0), $10, $25, $50, or ranges ($10 or less / $25 or more)
  - Number of character combinations — 4, 5, 6, or 7
  - Billing type — annual or one-time
  - Personalizable — yes / no
  - Disabled symbol available upon request — yes / no
- **Sort** by name, fee (low to high / high to low), or character count
- **Two views** — card grid or a sortable data table
- **Direct links** — each plate links to its official DMV detail page

## Data captured per plate

| Field | Description |
|-------|-------------|
| Name | Plate title |
| Category | Special Interest, College, Military, or Other |
| Plate fee | Annual or one-time fee, in addition to registration |
| Character combinations | Max characters available on the plate |
| Personalization available | Whether the plate can be personalized |
| Disabled symbol | Whether a disabled symbol is available upon request |

The personalized plate fee is a flat $10 annually across all plates.

## Usage

Open `index.html` in any browser. Everything is self-contained in a single file, no build step or server required.

## Hosting

This is a static site, so it can be hosted for free on GitHub Pages, Cloudflare Pages, Netlify, or similar. To publish on GitHub Pages: put `index.html` in the repo, then enable Pages under **Settings → Pages → Deploy from a branch**.

## Notes

- Plate images are currently loaded directly from the Virginia DMV's servers.
- This is an unofficial project and is not affiliated with or endorsed by the Virginia DMV. All plate data, images, and links belong to the Virginia Department of Motor Vehicles.

## License

Provided as-is for personal, informational use.
