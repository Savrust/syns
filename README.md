# SYNS - Top Page

A landing page for SYNS real estate investment company in Fukuoka, Japan.

## Features

- Modern, responsive design matching the original promotional graphic
- Japanese text content about Fukuoka real estate investment
- Dark green overlay with white text
- Yellow price box highlighting monthly pricing starting from 1,500 Yen
- SYNS branding in the top left corner

## Structure

- `index.html` — Main landing page markup (all sections live here)
- `styles.css` — Primary styling and responsive rules for the landing page
- `promo-styles.css` — Standalone stylesheet for the promo/mobile mock
- `assets/img/` — Image assets used across the page (figures, backgrounds, icons)
- `assets/person/` — Customer photos

## Usage

Open `index.html` in a browser. No build steps are required.

## Project Layout

```
.
├── index.html
├── styles.css
├── promo-styles.css
└── assets
    ├── img/        # Page illustrations, icons, diagrams
    └── person/     # Customer photos
```

## Editing Notes

- Keep `styles.css` as the single source for layout and responsiveness of `index.html`.
- Use `promo-styles.css` only if you need the alternate promo view; it is not imported by `index.html`.
- When adding new images, place them under `assets/img/` and use relative paths in HTML.
- Target mobile tweaks at `max-width: 425px` and stack horizontally aligned blocks below 424px when needed.

## Design Elements

- Background: Modern building with blue sky (using Unsplash placeholder)
- Dark green overlay box (#2d5a3d) with white Japanese text
- Yellow price box (#FFFACD) with dark green text
- SYNS logo and company name in the top left

## Responsive

The page is fully responsive and adapts to mobile, tablet, and desktop screen sizes.

