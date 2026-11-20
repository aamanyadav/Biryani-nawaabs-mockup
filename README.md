# Biryani Nawaabs — Website

The production website for **Biryani Nawaabs**. Theme: *Royal Heritage of Lucknow × Modern Luxury*.

> "From the Royal Kitchens of Lucknow to the World."

## Live Preview

Serve the folder with any static server (assets load from `assets/`, so open it over HTTP rather than double-clicking the file):

```
python -m http.server 8080
```

If hosted via GitHub Pages, the live link will be:

```
https://aamanyadav.github.io/Biryani-nawaabs-mockup/
```

## What's Inside

A fully responsive, single-page website covering:

- **Hero** — brand illustration, heading, and an Order Now CTA
- **Our Story** — an 8-stage scroll timeline (Ancient Lucknow → Future Global Brand)
- **Why Choose Us** — 6 core USPs with icons, plus an animated stats counter
- **Menu** — signature dishes with prices, veg/non-veg marks, and an order bar (Zomato / Swiggy / WhatsApp / Call)
- **Franchise** — overview plus a full application form (city, budget, format)
- **Gallery** — photo/moment placeholders
- **Testimonials** — carousel with dots, prev/next and pause controls
- **FAQ** — 6 questions with matching FAQPage structured data
- **Locations** — outlet cities
- **Footer / Contact** — working inquiry form (Web3Forms), address block, social links
- **Sticky mobile CTA bar** — Order / Call / WhatsApp on small screens

## Design System

| Token | Value |
|---|---|
| Primary — Royal Maroon | `#5B0F19` |
| Secondary — Antique Gold | `#C89B3C` |
| Background — Ivory | `#F8F3EA` |
| Text — Charcoal | `#1E1E1E` |
| Accent — Sand Beige | `#D8C2A3` |
| Premium Accent — Emerald | `#0E5C47` |

**Typography:** Cinzel (headings) · Cormorant Garamond (script accents) · Poppins (body & buttons) — via Google Fonts.

**Signature motif:** recurring Mughal-arch dividers and jaali (lattice) texture, tying every section back to the brand's heritage.

## Tech Stack

Plain **HTML, CSS, and vanilla JavaScript** — no frameworks, no build tools, no npm install. Images live in `assets/` as optimized files (the HTML itself is ~55 KB).

- Scroll-reveal animations via `IntersectionObserver`
- Animated stat counters
- Auto-rotating testimonial slider
- Accessible mobile nav (keyboard + screen-reader friendly)
- `prefers-reduced-motion` respected throughout

## Accessibility & SEO

- Skip link to `<main>`, visible focus states, labeled form fields with live status regions
- WCAG 2.2 AA contrast fixes, 44px touch targets, carousel pause control, reduced-motion support in CSS *and* JS
- Organization + Restaurant + FAQPage JSON-LD, keyword metadata, `robots.txt`, `sitemap.xml`, branded `404.html`

## Project Status

Production-track build with **placeholder business data**. Before launch, replace
every value listed in [PLACEHOLDERS.md](PLACEHOLDERS.md) — phone/WhatsApp/address,
Web3Forms access key, Zomato/Swiggy URLs, menu prices, verified stats and
testimonials, FSSAI number, and real photography.

## License

All rights reserved. This code and all brand assets (name, logo, illustrations) belong to Biryani Nawaabs and may not be reused, copied, or redistributed without permission.

## Credits

Concept document, brand direction, and illustration: Biryani Nawaabs team.
Site built By Aman Yadav
