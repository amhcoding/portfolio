# Hauschel Studios portfolio

Static site, no build step. Four pages:

- `index.html` — Home
- `film-photo.html` — Film & Photo (with category filter)
- `learning.html` — Instructional Design
- `about.html` — About (names Alex Hauschel as the studio's owner)

## Deploy on GitHub Pages

1. Create a repo and upload these files to the root (keep `index.html` at the top level).
2. Settings → Pages → Deploy from a branch → `main` / `/ (root)`.
3. For your own domain, add it under Pages → Custom domain and point DNS at GitHub Pages.

If you want Instructional Design on a subdomain, host `learning.html` (renamed `index.html`) in a second repo and change the nav links to the full URLs.

## Replace before launch

Search all pages for text in square brackets:

- `[YOUR EMAIL]` — contact address (appears in `mailto:` links on every page)
- `[PROJECT TITLE]`, `[CLIENT]`, `[YEAR]` — gallery and project tiles
- `[COURSE TITLE]`, `[AUDIENCE]`, Problem / Approach / Result text — case studies on `learning.html`
- `[INSTAGRAM]`, `[VIMEO / YOUTUBE]`, `[LINKEDIN]` — social links (currently `href="#"`)
- Image and video placeholders (hatched boxes with labels) — swap each for an `<img>` or video embed
- `[PORTRAIT OF ALEX · 4:5]` — your portrait on the About page

Accent colours live in the inline styles (`#FF5B3A` on the dark pages, `#B53418` on the Instructional Design page); a find-and-replace changes them everywhere.
