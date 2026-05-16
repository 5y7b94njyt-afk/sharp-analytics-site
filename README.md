# Tessera

One-page marketing site for Tessera — institutional intelligence platform for prediction markets.

## Overview

Tessera builds the Detection Suite: real-time identification of informed trading activity across prediction markets. The flagship product, **Sharp Money**, applies this technology to decentralized prediction markets (Polymarket). **SharpBook** extends coverage to sports markets.

## Running

Static site — no build step required. Open `index.html` in a browser or serve with any static file server:

```bash
python3 -m http.server 8000
# or
npx serve .
```

## Tech

- Pure HTML + CSS + vanilla JS
- No framework dependencies
- Google Fonts (Inter) via CDN
- Intersection Observer for scroll animations
- Mobile responsive
