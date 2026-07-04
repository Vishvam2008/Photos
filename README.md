# Photo Gallery (Static) — Vercel

This project is a **static** HTML/CSS photo gallery deployed directly on **Vercel**.

## Project structure
- `index.html` — gallery markup
- `style.css` — styling
- `images/` — all image assets
- `robots.txt`, `sitemap.xml` — SEO
- `manifest.webmanifest` — PWA manifest
- `vercel.json` — Vercel configuration (clean URLs, security headers, caching)

## Deploy to Vercel
1. Create a GitHub repository (or push to an existing one).
2. Push the contents of this folder.
3. In Vercel: **New Project** → select this repository.
4. Framework preset: **Static**.
5. Deploy.

## Notes
- Canonical URL and OpenGraph/Twitter image URLs use `https://example.com/` placeholders. Update when you know your domain.
- Images are lazy-loaded via `loading="lazy"`.

