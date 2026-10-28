# Spring Harbor Studios website

Static GitHub Pages website, deployed from main / root. Work directly on main; do not create branches or pull requests.

## Paredo migration — October 27, 2026

Paredo’s product, privacy, terms, and support pages now live at https://getparedo.app/. The Studio homepage and its general privacy/terms pages link directly to the corresponding destination. Both `/paredo/` and legacy `/simplify/` paths retain immediate HTML redirects, canonical URLs, and usable fallback links to the matching new pages, avoiding redirect chains. GitHub Pages serves these as static pages; these are HTML redirects rather than HTTP 301 responses.

Redirected product pages are excluded from this site’s sitemap. The general Studio privacy and terms pages remain here; Paredo’s subscription terms still refer to the Studio general terms.

The Paredo card links to the public Chrome Web Store listing and no longer says Coming soon. Support email is unchanged.
