# North Standard Brand Guide (GitHub Pages)

This folder is ready to publish as a static GitHub Pages site.

## Files in this folder
- `index.html` - the full single-file brand guide page
- `assets/lettermark.png` - add your lettermark image
- `assets/wordmark.png` - add your wordmark image
- `assets/favicon.png` - add your favicon/badge image
- `.nojekyll` - ensures GitHub Pages serves files as-is

## 1) Add your images
Put your three logo files in `assets/` using exactly these names:
- `lettermark.png`
- `wordmark.png`
- `favicon.png`

## 2) Publish on GitHub Pages (quick path)
1. Create a new GitHub repo.
2. Upload everything inside this folder to the repo root.
3. In GitHub: `Settings` -> `Pages`.
4. Under `Build and deployment`, choose:
   - Source: `Deploy from a branch`
   - Branch: `main` (or `master`), folder: `/ (root)`
5. Save and wait 1-2 minutes.

Your site URL will be shown in the Pages settings.

## 3) Optional: publish from a `/docs` folder
If you prefer, move these files into `/docs` in your repo and set Pages source to `/docs`.

## 4) Update brand values later
In `index.html`, update this JS config block near the bottom:

```js
const LETTERMARK_SRC = "./assets/lettermark.png";
const WORDMARK_SRC = "./assets/wordmark.png";
const FAVICON_SRC = "./assets/favicon.png";
const BRAND = { name: "North Standard", tagline: "Clear Direction · Higher Standard" };
```
