# Odoo Style Landing - Technical Assessment

## Overview
Responsive landing page implementation based on a visual reference, focused on clean structure, reusable styles, and visual consistency across sections.

## Tech Stack
- HTML5
- SCSS (Sass)
- Bootstrap 5 (CDN) + Bootstrap Icons

## How to Run
1. Install dependencies:
   `npm install`
2. Build styles (one time):
   `npm run build:css`
3. Or run Sass in watch mode:
   `npm run watch:css`
4. Open `index.html` in the browser.

## What Was Delivered
- Responsive hero, feature blocks, awards, FAQ, and footer sections.
- Functional mobile navbar and FAQ accordion.
- SCSS architecture split by responsibility:
  - `scss/base/_variables.scss`
  - `scss/base/_layout.scss`
  - `scss/components/_buttons.scss`
  - `scss/sections/_header-menu.scss`
  - `scss/sections/_header-main.scss`
  - `scss/sections/_video.scss`
  - `scss/sections/_download-app.scss`
  - `scss/sections/_award.scss`
  - `scss/sections/_helpful.scss`
  - `scss/sections/_footer-main.scss`
  - `scss/custom.scss` (entry point)
- Project cleanup: removed unused placeholders/files and updated documentation.

## Validation Performed
- Manual visual review (desktop + responsive breakpoint).
- Interaction checks for navbar collapse and accordion behavior.
- SCSS compilation verified without errors (`build:css` and `watch:css` ready).

## Notes
- To match spacing and proportions with the original design (Figma), use browser extensions like **Grid Ruler** and **Grid System** during visual QA.

## Author
- Poncho, Dev