# Biryani Nawaabs — Website Mockup

A single-file, self-contained website concept for **Biryani Nawaabs**, built from the brand's concept document. Theme: *Royal Heritage of Lucknow × Modern Luxury*.

> "From the Royal Kitchens of Lucknow to the World."

## Live Preview

Open `index.html` directly in any browser — no build step, no server, no dependencies to install. If hosted via GitHub Pages, the live link will be:

```
https://github.com/aamanyadav/Biryani-nawaabs-mockup
```

## What's Inside

A fully responsive, single-page website covering:

- **Hero** — brand illustration, heading, and primary CTAs
- **Our Story** — an 8-stage scroll timeline (Ancient Lucknow → Future Global Brand)
- **Why Choose Us** — 6 core USPs with icons, plus an animated stats counter
- **Menu** — signature dishes (biryanis, kebabs, Firni, Sheermal) in premium hover cards
- **Franchise** — investment/support overview with a call-to-action
- **Gallery** — photo/moment placeholders
- **Testimonials** — auto-rotating customer quotes
- **Locations** — outlet cities
- **Footer / Contact** — inquiry form and social links
- **Sticky mobile CTA bar** for quick access to Menu / Franchise on small screens

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

Plain **HTML, CSS, and vanilla JavaScript** — no frameworks, no build tools, no npm install. The hero illustration and logo are embedded directly as base64 data URIs, so the file is fully portable: copy `index.html` anywhere and it works.

- Scroll-reveal animations via `IntersectionObserver`
- Animated stat counters
- Auto-rotating testimonial slider
- Accessible mobile nav (keyboard + screen-reader friendly)
- `prefers-reduced-motion` respected throughout

## Accessibility & SEO

- Skip-to-content link, visible focus states, labeled form fields
- WCAG AA-compliant color contrast across the palette
- Meta description, Open Graph tags, and favicon included

## Project Status

This is a **front-end concept mockup**, not a production build. Known gaps before real launch:

- [ ] Replace illustrated dish placeholders with real food photography
- [ ] Wire the contact form to an actual backend/email service
- [ ] Replace placeholder gallery/location content with real assets and outlet data
- [ ] Add a real map integration for the Locations section

## License

All rights reserved. This code and all brand assets (name, logo, illustrations) belong to Biryani Nawaabs and may not be reused, copied, or redistributed without permission.

## Credits

Concept document, brand direction, and illustration: Biryani Nawaabs team.
Site built By Aman Yadav
