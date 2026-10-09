# Dropshipping model

We hold no stock. Supplier ships directly to the customer.

## Store settings already applied
- Inventory tracking is OFF on all 10 draft products (so they never show "sold out").
- FAQ states 7–12 business day delivery from partner suppliers.
- Shipping policy draft (docs/policies.md) updated to match.

## Still to do (needs the owner)
- [ ] Pick suppliers per SKU and confirm real cost, stock, shipping time, COD support in India
      (options to evaluate: IndiaMART/Alibaba sellers, Meesho/Shopify-app-based Indian dropship suppliers,
      CJ Dropshipping / Zendrop with India shipping). Do not publish products without a verified supplier.
- [ ] Record supplier cost per SKU and check margin after: GST, payment fee (~2%), COD fee/RTO losses,
      ad cost. Treat current prices as placeholders.
- [ ] Order flow: connect supplier app (or manual ordering) and test one order end to end.
- [ ] Return/RTO process with each supplier; align refund policy with supplier terms.
- [ ] Use real product photos from the supplier; never use another brand's trademarked images.
- [ ] Ensure supplier invoices/GST are compatible with your own GST registration.

## Supplier platform research (2026-10-06)
- Roposo Clout reportedly stopped accepting new orders on 2026-04-01 (marketplace, listings, order placement, invoices inactive).
  Reasons cited by sellers' blogs: high COD returns/RTO losses, thin margins, platform dependency. Verify before relying on it;
  could not open the Shopify app listing from this environment.
- Alternatives named in third-party blogs (unverified, check each yourself): Snazzyway, GridRay, Dropdash, IndiaMART suppliers, Meesho.
- Lesson for us: plan for RTO/COD returns in pricing; consider prepaid-first (small discount for UPI/prepaid) and pin-code COD limits.

## Supplier decision (2026-10-09) — PILOT, not a commitment
Pick: Dropdash (free Shopify app, India-based, COD + NDR/RTO handling, Pan-India shipping) as pilot fulfilment partner.
Evidence is thin and mixed: app-store ratings reported ~3.1–3.6 on 5–13 reviews; complaints about delivery issues,
product availability; some reviews look templated. No source confirmed electronics/home-kitchen coverage — VERIFY.
Not chosen: GridRay (dealer model, catalog appears sports/brands, no Shopify app found); Snazzyway (fashion-focused);
Dropship India (3.3★, RTO/return penalties); vFulfill (paid tiers).
Gate before any product goes ACTIVE: (1) catalog has the SKU, (2) order 1 sample, (3) 3 test orders incl. 1 COD,
(4) written RTO/return terms, (5) margin check. If Dropdash fails, fall back to IndiaMART/Meesho sourcing per SKU.
