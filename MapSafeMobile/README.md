# MapSafe Mobile guide

This is the GitHub Pages guide for MapSafe Mobile. It follows the layout and plain-language style of the MapSafe QGIS guide, adapted for the mobile workflow and the current North Whangārei evidence set.

## Contents

- `index.html` – guide content and navigation
- `css/style.css` – responsive layout and visual style
- `js/main.js` – galleries, navigation highlighting and screenshot lightbox
- `images/mobile` – 31 core MapSafe Mobile screenshots
- `images/community` – premium multi-account access screenshots
- `images/web` – NextGIS Web resource screenshots
- `images/mapsafe-mobile-architecture.png` – architecture figure retained for future use
- `downloads/MapSafeMobile-3.2.1.apk` – signed release APK for direct research installation
- `downloads/SHA256SUMS.txt` – checksum for verifying the APK download

## Publishing

Copy this directory to `MapSafeMobile/` in `sharmapn/sharmapn.github.io` and commit it to the repository's `main` branch. GitHub Pages will publish it at:

`https://sharmapn.github.io/MapSafeMobile/`

The guide is static and has no build step or external JavaScript dependency. It is suitable for GitHub Pages and can also be opened locally by opening `index.html` in a browser.

The direct APK download is intended for controlled research and field testing. Google Play remains the preferred distribution channel for general users because it provides familiar installation, review, Play Protect integration and automatic updates.

## Evidence note

The guide documents the research implementation. It should not be read as a claim that masking guarantees anonymity, that ACLs replace community governance, or that blockchain notarisation proves the truth of an observation.
