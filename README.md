# CITYELEC | Website presentation

This is an independent design proposal by Anya Agency for an appointment with CITYELEC. It is not the company's official website. The proposed TCE scope, service descriptions, workflow and graphic identity require confirmation with the prospect. Stock photographs are explicitly presented as inspiration, not completed CITYELEC projects.

- Static HTML, CSS and vanilla JavaScript.
- Relative local assets; no build system required.
- No analytics, tracking cookies, third-party runtime resources or server-side form collection.
- Form validation and email preview happen locally. Sending requires an explicit action in the visitor's own email client.
- `noindex`, `nofollow`, `noarchive`, `nosnippet` metadata plus a robots.txt disallow. This reduces indexing; it is not access control.

## Images

Images sourced from Unsplash and converted to local WebP assets:

- `assets/hero.webp`: https://images.unsplash.com/photo-1600585154340-be6161a56a0c
- `assets/interior.webp`: https://images.unsplash.com/photo-1600210492486-724fe5c67fb0
- `assets/bathroom.webp`: https://images.unsplash.com/photo-1620626011761-996317b8d101
- `assets/detail.webp`: https://images.unsplash.com/photo-1600566753086-00f18fb6b3ea

Unsplash license: https://unsplash.com/license

## Typeface

Manrope, locally hosted from Google Fonts. Font license: `assets/OFL-Manrope.txt`.

## Run locally

`python3 -m http.server 8080`

Open `http://localhost:8080/`.
