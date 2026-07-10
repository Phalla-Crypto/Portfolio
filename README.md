# Phalla Song — Portfolio

Personal portfolio for **Phalla Song** — Business Intelligence Team Lead & Data Architect
at Goodhill Enterprise, Phnom Penh, and former actuary at AIA Cambodia.

A single, self-contained `index.html` with a bold, data-driven design.

## Highlights

- **Bold data-driven theme** — deep-navy base with electric cyan / lime / magenta accents
- **Dark / light mode** — sun/moon toggle in the nav, tuned light palette, remembered via `localStorage` with a no-flash init script (defaults to dark)
- **Monospace display type** — JetBrains Mono headings in uppercase for an engineered, terminal feel
- **Motion** — scroll-reveal sections, animated skill bars, a logo-chip tech marquee, and chart / sparkline motifs
- **Fully responsive** with a mobile nav, active-section highlighting, and a sticky header
- **No build step, no runtime CDN** — Tailwind CSS is precompiled and inlined, and every icon is inline SVG. The only external request is optional Google Fonts, which degrades gracefully to system fonts.
- **Accessible** — honors `prefers-reduced-motion`, includes meta/Open Graph tags, and works without JavaScript

## Sections

Hero · Stats · About · Selected Work (NEXUS BI) · Case Studies · Skills ·
Actuarial background · Speaking & Community · Journey · Education & Credentials · Contact

## Case studies

Four end-to-end projects, each linking to the full deck in `pdf/`:

- **Optimizing Marketplace Efficiency** — Grab ride-hailing; Power BI + Python EDA over 9,894 bookings
- **Demand Forecasting System** — Goodhill FMCG; automated ML forecasting, ~90% accuracy across 400+ SKUs
- **Insurance Claim Prediction** — AIA Cambodia; two-stage classification + regression ML pipeline
- **After-Sale Service Performance** — Mitsubishi Motors Cambodia; Power BI + DAX over 11,467 service records

Project cover thumbnails in `images/covers/` are rendered from the first/key page of each PDF.

## Assets

- `pdf/` — project decks and the ITC guest-lecture deck (linked from the page)
- `images/` — headshot, company/university logos, certificates, speaking & defense photos
- `images/covers/` — auto-generated project thumbnails

## Deploy

It's a static page — open `index.html` directly, or host the folder anywhere
(e.g. GitHub Pages). Nothing to install.

## Editing

All content and copy live in `index.html`. The Tailwind utility styles are
precompiled into the `<style>` block; design tokens (the custom `ink` / `panel`
/ `line` colors and `cyan` / `lime` / `magenta` accents) can be regenerated with
the Tailwind CLI if you want to tweak the system.
