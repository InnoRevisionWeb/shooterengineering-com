# Shooter Engineering — Deployment Package

Copyright (c) 2026 InnoRevision, Inc. All Rights Reserved.

## Purpose

Static, one-page Shooter Engineering automotive engineering heritage website. The approved V4 visual design and page copy have been retained, including the panoramic circuit-trace car hero.

## Files

- `index.html` — semantic HTML5, site copy, metadata, copyright notice.
- `styles.css` — formatted CSS, responsive layout and theme tokens.
- `assets/shooter-circuit-car.webp` — optimized panoramic hero artwork.
- `assets/favicon.svg` — simple, legacy-logo-free S favicon.
- `robots.txt`, `sitemap.xml` — search engine discovery.
- `.nojekyll` — GitHub Pages static site configuration.

## Preview and hosting

Open `index.html` locally to review. The Google Fonts stylesheet uses an external connection; fallback fonts are defined in CSS if unavailable. No JS runtime, dependencies, build process, analytics, tracking, cookies, or contact-form service are required.

For GitHub Pages:

1. Create a repository in the `InnoRevisionWeb` organization (for example `shooterengineering-com`).
2. Upload the contents of this package to the repository root, including `.nojekyll`.
3. Set GitHub Pages to deploy from the `main` branch and root folder.
4. Configure `shooterengineering.com` as the custom domain in GitHub Pages (the repository already contains `CNAME`).
5. Before making DNS changes, back up GoDaddy records; modify only necessary website A/AAAA and `www` records as instructed by GitHub Pages. Leave unrelated mail, TXT, and nameserver records intact.
6. Verify HTTPS certificate issuance, enforce HTTPS, and test both apex and `www`, including mobile layout, anchors, hero image, external InnoRevision link, and email link.

## Maintenance

The canonical URL, sitemap URL and CNAME are configured for `https://shooterengineering.com/`. Update all three together if the domain changes. Update the copyright year as appropriate. Recompress replacement hero artwork as WebP and keep its intrinsic dimensions in HTML current.

All website copy and branding are editable directly in `index.html`; palette colors and layout live in `styles.css`. No changes were made to the live domain or DNS.
