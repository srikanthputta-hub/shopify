# TrendNest — store design spec

Theme: Horizon (currently live). Apply in Online Store → Themes → Customize.
The connector cannot edit a live theme and could not create a theme copy, so this is a spec to apply by hand.

## Brand
- Name: TrendNest. Tagline: "Trending finds, delivered across India."
- Tone: friendly, upbeat, value-first. Price shown in ₹, GST-inclusive.
- Colors: primary coral/orange #F4511E (CTAs, sale badges); dark #1F2933 (text, header);
  warm off-white #FFF8F3 (page background); accent teal #00897B (trust badges, success).
- Fonts: headings a bold geometric sans (e.g. Poppins/Montserrat); body a clean sans (e.g. Inter).
- Logo: simple text wordmark "TrendNest" in dark, with "Nest" in coral. Favicon: coral "T".

## Homepage sections (top to bottom)
1. Announcement bar: "Free COD on eligible pin codes · Pan-India delivery" (only keep claims that are true).
2. Header: logo, Main menu (already set), search, cart.
3. Hero banner: "Trending finds for your home & everyday" + button "Shop now" → /collections/all.
4. Collection grid: the 5 collections (Kitchen, Home Decor, Phone & Car, Wellness, Mini Gadgets).
5. Featured products: 4 items (massage gun, sunset lamp, mini chopper, charger).
6. Trust row: Pan-India delivery · COD available · Easy 7-day returns · Secure payments (UPI/cards).
7. Short brand blurb from About Us, then footer.
- Footer menu is already set: About Us, FAQ, Contact, Search. Add policy links once policies exist.

## Product page rules
- 4–6 real supplier photos, benefit-led title, 3–4 bullet benefits, delivery estimate "7–12 business days".
- Show compare-at price only if a genuine previous price existed.
- Avoid unverifiable claims (e.g. medical benefits for massagers).

## Already applied via API
- Main menu: Home, Shop (+5 collections), About Us, FAQ, Contact (fixed broken /pages/contact link).
- Footer menu: About Us, FAQ, Contact, Search.

## Also applied via API (later pass)
- Policy text published as regular pages (Shipping, Refund & Return, Privacy, Terms of Service) and linked in the footer,
  because the connector cannot write real Shop Policies. Still paste docs/policies.md into Settings → Policies so
  checkout shows them, then these pages can be removed.
- All 10 products: benefit-bullet descriptions and SEO title/meta description. Still DRAFT, no images, no supplier yet.
