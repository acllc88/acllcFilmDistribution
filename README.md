# AC LLC — Film & Series Distribution Website

Static marketing website for AC LLC (US film & series distribution).

## Pages
- `index.html` — landing page
- `privacy.html` — privacy policy
- `terms.html` — terms
- `favicon.svg`, `og-image.svg` — brand/assets
- `instagram-promo.png` / `instagram-promo.svg` — promotional social asset

## Local preview
Open `index.html` directly, or serve locally:

```bash
python3 -m http.server 8080
# then visit http://localhost:8080
```

## Deploy

### GitHub
```bash
git init
git add .
git commit -m "Initial site"
git branch -M main
git remote add origin <your-repo-url>
git push -u origin main
```

### Vercel
- Import the GitHub repository in [Vercel](https://vercel.com/new)
- Framework preset: **Other** (static)
- Root directory: `./`
- Build command: *(none)*
- Output directory: *(leave default / root)*

`vercel.json` is included for clean URLs and basic security headers.
