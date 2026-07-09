# Zihui Lu — Portfolio Website

A personal portfolio site for Zihui Lu, a new-grad software engineer based in Toronto, Canada.

**Live site:** https://alize198.github.io/ *(adjust if using a custom domain or different host)*

## Tech stack

Plain HTML, CSS, and a small amount of vanilla JavaScript — no build step, no framework, no dependencies.

- `index.html` — page structure and content
- `style.css` — all styling
- `assets/` — images and résumé PDF used by the site

## Running locally

No build tools needed. Just open the file directly:

```bash
open index.html
```

Or serve it with any static file server, e.g.:

```bash
python3 -m http.server
```

then visit `http://localhost:8000`.

## Deployment

This site is static and can be hosted on any static host (GitHub Pages, Netlify, Vercel, etc.). For GitHub Pages, enable Pages for this repo and point it at the `main` branch.
