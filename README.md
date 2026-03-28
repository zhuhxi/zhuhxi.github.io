# Personal Homepage

Minimal static personal homepage ready for GitHub Pages.

## Recommended repository name

Use one of these:

- `zhuhxi.github.io` → site opens at `https://zhuhxi.github.io/`
- any other repo name, for example `homepage` → site opens at `https://zhuhxi.github.io/homepage/`

If you want the homepage at the root domain, use `zhuhxi.github.io`.

## What is included

- `index.html` — homepage
- `404.html` — not found page
- `favicon.svg` — favicon
- `.nojekyll` — disables Jekyll processing
- `robots.txt`
- `sitemap.xml`
- `.github/workflows/pages.yml` — GitHub Actions deployment workflow

## Deploy

### Option A: easiest (recommended)

1. Create a new GitHub repository
2. Push this folder to the `main` branch
3. On GitHub, go to **Settings → Pages**
4. Under **Build and deployment**, choose **GitHub Actions**
5. Wait for the workflow to finish
6. Open the generated Pages URL

### Option B: branch deploy

1. Create a new GitHub repository
2. Push this folder to the `main` branch
3. On GitHub, go to **Settings → Pages**
4. Under **Build and deployment**, choose **Deploy from a branch**
5. Select branch `main` and folder `/(root)`
6. Save and wait for the site URL

## Before publishing

If you use a custom username repo, update this line in `sitemap.xml`:

- `https://zhuhxi.github.io/`

This project is already prepared for your root GitHub Pages URL.
