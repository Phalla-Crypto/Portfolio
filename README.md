# Phalla Song — Portfolio

Personal portfolio for **Phalla Song** — Business Intelligence Team Lead & Data Architect
at Goodhill Enterprise, Phnom Penh, and former actuary at AIA Cambodia.

A single, self-contained `index.html` with a bold, data-driven design.

## Highlights

- **Bold data-driven theme** — deep-navy base with electric cyan / lime / magenta accents
- **Motion** — animated KPI counters, scroll-reveal sections, animated skill bars, and chart / sparkline motifs
- **Fully responsive** with a mobile nav, active-section highlighting, and a sticky header
- **No build step, no runtime CDN** — Tailwind CSS is precompiled and inlined, and every icon is inline SVG. The only external request is optional Google Fonts, which degrades gracefully to system fonts.
- **Accessible** — honors `prefers-reduced-motion`, includes meta/Open Graph tags, and works without JavaScript

## Sections

Hero · Stats · About · Selected Work (NEXUS BI) · Skills · Actuarial background · Journey · Contact

## Deploy

It's a static page — open `index.html` directly, or host the folder anywhere
(e.g. GitHub Pages). Nothing to install.

## Editing

All content and copy live in `index.html`. The Tailwind utility styles are
precompiled into the `<style>` block; design tokens (the custom `ink` / `panel`
/ `line` colors and `cyan` / `lime` / `magenta` accents) can be regenerated with
the Tailwind CLI if you want to tweak the system.
