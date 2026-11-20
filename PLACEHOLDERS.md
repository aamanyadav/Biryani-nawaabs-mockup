# Go-Live Checklist — Placeholder Values to Replace

Every item below is a **placeholder** currently shipped in the site. Replace each
with the real value before (or right after) launch. Search `index.html` for the
quoted strings.

## 1. Contact details (highest priority)

| Placeholder | Where | Replace with |
|---|---|---|
| `+915224000000` / `+91 522 400 0000` | Order bar "Call to Order", sticky bar "Call", footer, JSON-LD | Real phone number |
| `wa.me/915224000000` | Order bar, sticky bar, footer WhatsApp icon | Real WhatsApp business number |
| `hello@biryaninawaabs.com` | Footer, JSON-LD contactPoint | Real email |
| `careers@biryaninawaabs.com` | Footer Careers link | Real careers email (or remove) |
| `Hazratganj, Lucknow, Uttar Pradesh` + `226001` | Footer address, JSON-LD | Real flagship address |
| `Open daily, 11:00 AM – 11:00 PM` + JSON-LD `11:00`/`23:00` | Footer, JSON-LD | Real hours |

## 2. Forms (every inquiry is lost until this is done)

- `YOUR_WEB3FORMS_ACCESS_KEY` appears **twice** (contact form + franchise form).
  Create a free key at <https://web3forms.com> with the email that should receive
  inquiries, and paste it into both hidden `access_key` inputs. Until then the
  forms show a polite "call or WhatsApp us" fallback instead of submitting.

## 3. Ordering links

- `https://www.zomato.com/` → the outlet's real Zomato page URL.
- `https://www.swiggy.com/` → the outlet's real Swiggy page URL.

## 4. Social profiles

- `https://www.instagram.com/biryaninawaabs` and
  `https://www.facebook.com/biryaninawaabs` — confirm these handles exist or
  update them (footer icons + JSON-LD `sameAs`).

## 5. Claims that must be verified or changed (legal/trust risk)

- Stats: **18+ years, 45+ outlets, 20+ cities, 2M+ biryanis** (Why-Choose section).
- "18-year heritage brand" in the franchise lede.
- Testimonials: Ananya R., Farhan M., Karan S., and the anonymous
  "Franchise Partner, Pune" quote — replace with real, permissioned reviews.
- Location cards: Lucknow, Delhi NCR, Mumbai, Bengaluru, Pune neighbourhoods —
  keep only real outlets.
- Menu prices (₹329 / ₹349 / ₹449 / ₹249 / ₹399 / ₹129 / ₹79) and portions —
  set real prices.
- `FSSAI Lic. No. 00000000000000` in the footer — real licence number (mandatory).

## 6. Domain & hosting

- Canonical/OG/schema URLs assume **https://www.biryaninawaabs.com/**. Confirm the
  domain is owned; for GitHub Pages add a `CNAME` file, enforce HTTPS, redirect
  non-www → www, then verify in Google Search Console and submit `sitemap.xml`.
- If launching on a different domain, update: canonical, og:url, og:image,
  twitter:image, both JSON-LD blocks, robots.txt and sitemap.xml.

## 7. Real photography (replaces illustrations)

- Hero (`assets/hero.jpg`) is an illustration — also used as the og share image.
- Dish cards use decorative SVGs; gallery tiles are text-only.
- Recommended shoot list: handi being unsealed (steam), dum-sealed pot, kebabs,
  dining hall, kitchen team, packaging.

## Deferred (tracked as future work, not placeholders)

- Privacy Policy + Terms pages (required once forms collect data — DPDP Act).
- Franchise economics table (investment/fee/royalty by format) — needs owner numbers.
- Google Maps embed — needs the real address.
- Separate `/franchise`, `/menu`, `/locations` pages for SEO.
- GA4 / Meta Pixel with click + lead events.
- Self-hosted, subset fonts.
