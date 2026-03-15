# shaanvaidya.github.io

Personal website. Static HTML/CSS — no build step.

## Deploy

```bash
git add . && git commit -m "..." && git push
# live immediately at shaanvaidya.com
```

## Structure

- `index.html` — main page
- `css/` — stylesheets (bootstrap + custom style.css)
- `assets/` — images, favicon
- `images/` — photos
- `docs/`, `papers/`, `slides/` — linked documents
- `cv.pdf` — current CV
- `SanFranciscoStreetTreeMap/` — just a robots.txt and sitemap.xml for the tree map subpath

## Infrastructure

- Domain `shaanvaidya.com` registered via Squarespace
- DNS managed through Cloudflare (free tier) — nameservers point from Squarespace → Cloudflare
- Cloudflare proxy is ON, so GitHub Pages shows an HTTPS warning — this is expected, Cloudflare handles SSL instead
- Email `me@shaanvaidya.com` is on Zoho Mail (free tier), forwarded to personal Gmail
- Tree map app is a separate repo: `SanFranciscoStreetTreeMap`, deployed to `gh-pages` branch, served at `shaanvaidya.github.io/SanFranciscoStreetTreeMap/`
