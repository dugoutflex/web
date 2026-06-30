# DUGOUTFLEX — web

Marketing / product-customizer site for **DugoutFlex** (Mississauga, ON).

Single self-contained static page — all styles, scripts, and images (base64) live in
[`index.html`](./index.html). No build step, no backend, no external dependencies
except Google Fonts.

## Live site

Deployed via **GitHub Pages**: https://dugoutflex.github.io/web/

## Local preview

Just open the file, or serve it:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Deploy

Pages publishes automatically from the `main` branch (root) on every push.
`.nojekyll` is present so the static file is served as-is without Jekyll processing.

## Notes

- The product customizer's preview-image map (`imgs` in the inline `<script>`) is
  currently empty, so the live preview thumbnail does not update yet. Hero and
  product-card imagery render fine.
