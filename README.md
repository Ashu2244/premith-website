# Premith Website

Static marketing site for Premith (Secure + Industries).

## Edit site

Change files under **`public/`** (`index.html`, `styles.css`, images).

## Cloudflare (Git → Workers)

- **Build command:** `npm install` (or empty)
- **Deploy command:** `npx wrangler deploy`
- **Production branch:** `main`

Static assets deploy from `public/` only (not `node_modules`).

```powershell
git add .
git commit -m "Update site"
git push
```