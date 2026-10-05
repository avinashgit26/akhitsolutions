# AKH IT Solutions — 2026 redesign

This package is a full static-site overhaul of the supplied AKH IT Solutions website.

## What changed
- Rebuilt all 22 HTML pages with a unified product-engineering visual system.
- New responsive header, navigation, mobile menu, footer, cards, service layouts, case studies, careers, article and legal templates.
- Reference-inspired visuals are stored in `website/images/redesign/`.
- Site-wide styles live in `website/css/redesign.css`; lightweight menu behaviour lives in `website/js/redesign.js`.
- Existing original assets and upload folders have been retained for compatibility.

## Run locally
From the `akhitsolutions` folder, run `python -m http.server 8000` and open `http://localhost:8000`.

## Key design tokens
- Background: `#fbfaf7`
- Primary blue: `#075cf6`
- Text: `#080b14`
- Max content width: `1410px`

## Notes
The HTML is framework-free and deploys to any static host. Email CTAs use `mailto:` links.
