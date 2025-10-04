# Personal Website Starter (.ca + GitHub Pages)

This kit is tailored for **sukritiverma.ca** and free hosting with **GitHub Pages**.

## Quick Deploy
1. Create a public GitHub repo (e.g., `personal-website`).
2. Upload all files in this folder.
3. **Settings → Pages** → Deploy from **main / root**.
4. When it loads at `https://USERNAME.github.io/personal-website`, set your custom domain.

## Custom Domain (www recommended)
- Add DNS at your registrar (Squarespace → Domains → DNS):
  - CNAME: `www` → `USERNAME.github.io`
- In GitHub **Settings → Pages → Custom domain**: `www.sukritiverma.ca` → **Enforce HTTPS**.
- Set up a **forward/redirect** from `sukritiverma.ca` → `https://www.sukritiverma.ca`.

> The included `CNAME` file helps GitHub Pages keep your custom domain set on deploy.

## Edit Content
- `index.html`: text & sections.
- `styles.css`: colors, fonts, spacing.
- `assets/favicon.png` and `assets/og-image.png`: replace with your images.

## Extras
- `robots.txt` and `sitemap.xml` for basic SEO.
- `404.html` for nice not-found pages.
