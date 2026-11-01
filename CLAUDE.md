# SyntaxWear

The home page of a fictional sneaker store, built while following a lesson of the DevQuest course. I wrote this file to give Claude Code the context it needs.

## Stack
- HTML and CSS. Vanilla JavaScript when needed (none yet).
- No build step and no dependencies.
- Published on Netlify from `public/`.

## Commands
- Run locally: serve `public/` with a local static server. The external SVG sprite does not load over `file://`.
- Formatting: Prettier defaults (VS Code).

## Structure
- `public/`: the published site.
  - `index.html`: the only page (home).
  - `assets/icons/sprite.svg`: SVG sprite, used with `<use>`.
  - `assets/images/`: `banners/` (hero) and `products/` (category and featured product images).
  - `css/`: `reset.css`, `tokens.css`, `base.css`, `layout.css` and `components/` (one file per home section).
  - `js/`: empty.
- `docs/`: project documentation (see Docs).
- `netlify.toml`: Netlify config, publishes `public/`.

## Conventions
- Component CSS is split into one file per section in `css/components/`, not a single `components.css`.
- Site content in European Portuguese (`lang="pt-PT"`). Code, class names and comments in English.
- Image paths in CSS are relative to the CSS file (`../../assets/images/...`). Never start a path with `/public/`.

## Docs
- `docs/features.md`: what each section of the home page does. Read before changing a section.
- `docs/components.md`: reusable components and their files. Read before creating a component.

## Status
- Course lessons finished. The home page has a header, hero, product categories, featured products and footer.
- Not published yet.
- All links point to `#`. The newsletter has no form handling. No JavaScript.
- Desktop layout only: there are no media queries.
