# Go-Live Checklist

Much of the site now uses **real data from the Biryani Nawaabs Google Business
Profile** (fetched 21 Nov 2026). This file tracks what is real, what is still a
placeholder, and what the owner must confirm. Search `index.html` for the quoted
strings.

## Now REAL (sourced from the Google profile — keep in sync with it)

- Phone / WhatsApp number: `+91 70804 62999` (`tel:+917080462999`, `wa.me/917080462999`)
- Flagship address: SHOP N-C-1, Kapoorthala Road, Chandralok, Lucknow, UP 226024
- Hours: daily 11:30 AM – 11:30 PM
- Rating/stats: 4.7★, 875+ Google reviews, 2 outlets, menu with 30+ dishes
- Gallery photos (assets/gallery/): facade day/night, dining hall, brass thali,
  veg & mutton biryani — taken from the profile's photo gallery
- Testimonials: real Google reviews by Aida, Drogo, Vikas Jaiswal
- Menu prices for Galouti Kebab (₹169–299), Chicken Biryani (₹299–499),
  Mutton Biryani (₹349–599), Kakori Kebab (₹489) — from the photographed menu card
- Locations section + embedded Google map; "Get directions" uses the owner's
  own share link (https://maps.app.goo.gl/c1W1wtuquGLPeq1t6)

## Still PLACEHOLDER — owner must supply

| Placeholder | Where | Replace with |
|---|---|---|
| `YOUR_WEB3FORMS_ACCESS_KEY` (×2) | contact + franchise forms | Free key from <https://web3forms.com> with the destination inbox. Until set, forms show a "call or WhatsApp us" fallback. |
| `hello@biryaninawaabs.com` / `careers@` | footer, JSON-LD, Careers link | Real email addresses |
| Veg Biryani ₹249, Firni ₹129, Sheermal ₹79 | menu cards | Real prices (menu card page 2 wasn't in the photos) |
| `FSSAI Lic. No. 00000000000000` | footer | Real licence number (mandatory) |
| Ashiyana outlet details | locations card | Exact address + closing time ("opens 12 PM" is all Google shows) |
| Hero illustration | assets/hero.jpg + og:image | Owner-approved (from concept doc); swap only if a real 1200×630 brand photo is preferred for shares |

## Owner must verify

- WhatsApp: confirm +91 70804 62999 is on WhatsApp Business (the wa.me links assume it).
- The stats refresh over time — update 875+/4.7★ when they change meaningfully.
- Canonical domain https://www.biryaninawaabs.com/ — confirm ownership; the
  Google Business Profile currently lists **no website**, so add this site to the
  profile once it is live (huge local-SEO win).
- Menu dish list: concept doc says the full menu content "we will share" — swap
  in the shared menu + photos when provided.

## Design decisions locked by the owner's concept doc (do not undo)

- Single-page site; nav anchors only (no separate menu page).
- Hero = the royal illustration; H1 = "Royal Taste. Crafted in Lucknow. Loved Across India."
- Hero buttons = Explore Menu + Become a Franchise. **No "Order Now" button anywhere.**
- Royal Maroon / Antique Gold / Ivory palette; Cinzel + Cormorant Garamond + Poppins.
