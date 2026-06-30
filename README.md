# Doris AY — Landing Page

Static landing page for **Doris AY**, hosted on GitHub Pages.

> **Status:** Live — Doris Landing Page V1 deployed to `index.html`.

## Project structure

```
doris-ay-website/
├── index.html          # Main landing page (replace with your HTML)
├── assets/             # Images, fonts, and other static files
│   └── .gitkeep
├── README.md
└── .gitignore
```

## Add your HTML

1. Paste or save your finished page as `index.html` in the repo root.
2. Put any images, CSS, or JS files in `assets/` (or update paths in your HTML to match).
3. Commit and push to `main`.

If your HTML references external styles or scripts with relative paths, keep those files alongside `index.html` or under `assets/` and update the paths accordingly.

## Preview locally

Open the page in a browser — no build step required:

```bash
# macOS
open index.html

# Or serve locally (optional)
python3 -m http.server 8080
# Then visit http://localhost:8080
```

## Deploy to GitHub Pages

After pushing to `main`:

1. Open the repo on GitHub: [rosspower11/doris-ay-website](https://github.com/rosspower11/doris-ay-website)
2. Go to **Settings → Pages**
3. Under **Build and deployment → Source**, choose **Deploy from a branch**
4. Set **Branch** to `main` and folder to **`/ (root)`**
5. Save — GitHub will publish the site at:

   **https://rosspower11.github.io/doris-ay-website/**

Changes pushed to `main` usually go live within a minute or two.

### Custom domain (optional)

To use your own domain (e.g. `www.dorisay.com`):

1. Add a `CNAME` file in the repo root containing the domain (one line, no `https://`).
2. In your DNS provider, add the records GitHub Pages shows under **Settings → Pages → Custom domain**.
3. Enable **Enforce HTTPS** once the certificate is issued.

## Quick push workflow

```bash
git add index.html assets/
git commit -m "Update landing page"
git push origin main
```

## Notes

- This repo is static HTML only — no build tools or dependencies.
- Keep file names lowercase and avoid spaces for reliable links.
- Large assets (hero images, etc.) belong in `assets/` to keep the root tidy.
