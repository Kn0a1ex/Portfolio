# Portfolio

Personal site for Alex (Kn0a1ex). Plain static HTML/CSS/JS, no build step, deployed to GitHub Pages
from `main` by `.github/workflows/pages.yml`.

## Editing

- `index.html` holds all the copy. Search for `TODO(alex)` for the bio, avatar, and contact spots.
- `css/style.css` has the theme tokens at the top under `:root`.
- `js/main.js` does the mobile nav, footer year, and reveal-on-scroll. The page works with JS disabled.

## Preview locally

```bash
python -m http.server 8000
```

Then open http://localhost:8000.
