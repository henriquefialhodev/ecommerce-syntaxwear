# SyntaxWear

Home page of a fictional sneaker store, built with HTML and CSS.

## About
I built this project while following a lesson of the DevQuest course. The page has a fixed header, a hero, product categories, a featured products grid and a footer with a newsletter field, social links and category links.

## Decisions
- Icons come from one external SVG sprite (`assets/icons/sprite.svg`), used with `<use>`.
- The CSS is split into reset, tokens, base, layout and one file per home section.
- The site is published on Netlify from `public/`.

## Run locally
Serve the `public/` folder with a local static server and open `index.html`. The SVG sprite does not load when the file is opened directly (`file://`).

## Pages
| Page | CSS | JS |
|---|---|---|
| `index.html` | `reset.css`, `tokens.css`, `base.css`, `layout.css`, `components/header.css`, `components/hero.css`, `components/product-category.css`, `components/featured-products.css`, `components/footer.css` | none |
