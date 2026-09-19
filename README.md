# Raina Ghasha Haris — Portfolio Website (v3, Marketing & Creative)

Static one-page portfolio (HTML/CSS/vanilla JS, no build step, no dependencies), rebuilt per
`PRD-Raina-Portfolio-Marketing-Creative-v3.md` on top of the v2 build. This version re-positions
the site from Corporate Communication/PR to **Marketing & Creative**, moves Selected Work earlier
in the page, and adds three new headline projects (TVC Cimory, Short Film Sariwangi Tea, String
Cafe digital campaign) sourced directly from `Portofolio_Raina_Ghasha_Haris_Final.pdf`.

## Structure

```
index.html
assets/
  css/style.css     design tokens + all component styles (unchanged from v2)
  js/main.js        nav scrollspy, mobile menu, scroll-reveal, lightbox, progress bar (unchanged)
  icons/favicon.svg
  img/               all photos, certificates and poster crops, optimized as JPG
    projects/cimory-tvc.jpg, sariwangi-film.jpg, stringcafe-storefront.jpg,
             stringcafe-interior.jpg  ← NEW, cropped directly from the source PDF's slides
```

## Deploy

Fully static site — upload the whole folder as-is to any static host:

- **Netlify / Vercel**: drag-and-drop the folder (or connect a repo) — no build command needed,
  output directory is `/`.
- **GitHub Pages**: push this folder to a repo and enable Pages on the branch/`root`.
- **Any shared/cPanel hosting**: upload the contents of this folder into `public_html/`.

No environment variables, no server, no database.

## Editing content

All copy lives directly in `index.html`. Colors and fonts are defined as CSS custom
properties at the top of `assets/css/style.css` under `:root` — change `--bg-deep`,
`--accent`, `--green` etc. to re-theme the whole site.

## Design system (unchanged from v2/PRD Section 9)

- Dominant background: azure navy `#123B63`
- Accent: gold/tan `#C5A46D`
- Secondary accent: deep green `#1B2E28`
- Display font: Fraunces · Body: Plus Jakarta Sans · Data/labels: IBM Plex Mono

## What changed in v3 — see `CONTENT-DECISIONS-v3.md`

Positioning switch to Marketing & Creative, section reorder (Selected Work now right after
About), three new headline creative projects with real links sourced from the PDF, competencies
regrouped, AI tools restored, phone/email contact **reversed back** to what the source PDF's own
"Get In Touch" slide states. **Read `CONTENT-DECISIONS-v3.md` before publishing** — one item
(contact email/phone) needs Raina's explicit final confirmation.
