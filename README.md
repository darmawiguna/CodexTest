# CodexTest

## UNESCO World Heritage Globe

This repository now includes a self-contained HTML page (`index.html`) that renders an interactive 3D globe populated with data from the [UNESCO World Heritage List XML feed](https://whc.unesco.org/en/list/xml/).

### Getting started

1. Open `index.html` in any modern browser with WebGL support.
2. The page will fetch the live XML feed, extract coordinates for each site, and render them as interactive points on the globe.
3. Hover a point to reveal site details (name, country, heritage category, and inscription year).

> **Note:** If the remote XML feed is temporarily unavailable or blocked by network restrictions, the page will display a status message indicating that the data could not be loaded.
