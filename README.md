# Air Duct Cleaning Charleston SC — Astro Site

Static Astro site for **aairductcleaningcharlestonnc.com**, optimized for Cloudflare Pages.

## Features
- Responsive, mobile-first design
- Deep navy + cyan color theme (clean-air inspired)
- OpenStreetMap embed for 775 Folly Rd d, Charleston, SC 29412
- SEO: meta tags, canonical, JSON-LD LocalBusiness schema, sitemap, robots.txt
- Fast static build for Google indexing
- Cloudflare Pages ready (static output, no adapter needed)

## Phone number
Placeholder: **(843) 555-0199** — replace across the site (search for `8435550199` and `555-0199`).

## Deploy to Cloudflare Pages
1. Push this folder to a GitHub/GitLab repo.
2. In Cloudflare Dashboard → Workers & Pages → Create → Connect to Git.
3. Build settings:
   - **Framework preset:** Astro
   - **Build command:** `npm run build`
   - **Build output directory:** `dist`
4. Add custom domain `aairductcleaningcharlestonnc.com`.
5. Submit `https://aairductcleaningcharlestonnc.com/sitemap-index.xml` in Google Search Console.

## Local development
```bash
npm install
npm run dev
```

## Build
```bash
npm run build
```
Output is in `dist/`.

## Notes
- Site is fully static (`output: 'static'` by default) — ideal for Pages and SEO.
- `@astrojs/sitemap` generates `/sitemap-index.xml` at build time.
- `public/robots.txt` points crawlers to the sitemap.
