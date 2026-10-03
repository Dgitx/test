# NOVA Growth — Sitemap-driven website

A responsive static marketing website generated from the uploaded 62-page sitemap.

## Run locally

```bash
python -m http.server 8080 -d .
```
Then open http://localhost:8080.

## Deploy to Cloudflare Pages

- Framework preset: None
- Build command: leave empty
- Build output directory: `/` (repository root)

Upload the contents of this folder or connect the repository to Cloudflare Pages.

## Included

- All concrete sitemap routes
- Representative `example` pages for dynamic `[slug]` routes
- Responsive header/mobile navigation
- Homepage, service, pricing, work, resource, form, portal and legal templates
- Working front-end ROI calculator
- Demo form states ready to connect to a backend/CRM
- `robots.txt`, XML sitemap, custom 404 and Cloudflare `_headers`

## Before production

Replace placeholder brand/contact details, connect forms + scheduling, add analytics/consent, and have final legal copy reviewed.
