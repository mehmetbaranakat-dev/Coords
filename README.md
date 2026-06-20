# Coords — OSGB36 ⇄ WGS84 Coordinate Converter

A browser-based tool for converting between British National Grid
(OSGB36 / EPSG:27700, eastings & northings) and WGS84 latitude/longitude
for use in Google Earth and site survey work.

## Features
- **Single point** — convert one coordinate either direction, with direct
  Google Maps / Google Earth links.
- **Batch (CSV)** — paste many points at once and download the results as CSV.
- **DXF → KML/KMZ** — upload a DXF; points and polylines are converted and
  exported as KML or KMZ for Google Earth (DXF layer names carried through).

## Notes
- Conversion uses a 7-parameter Helmert transform (OSGB36 ↔ WGS84),
  accurate to well under a metre across Great Britain — suitable for
  general layout and verification, not legal/survey-grade setting-out.
- Runs entirely in the browser. No coordinate or site data leaves the page.

## Usage
Open the live tool: https://mehmetbaranakat-dev.github.io/Coords
