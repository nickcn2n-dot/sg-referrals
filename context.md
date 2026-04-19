# Singapore Referrals Site — Context

## Purpose
Build and maintain a small, credible Singapore-facing referral site that earns through real referral / affiliate links.

## Current direction
- Keep the site intentionally small and trustworthy.
- Prefer a curated set of live offers over a giant coupon dump.
- Current live offers:
  - Trust Bank (code)
  - YouTrip (live link)
  - Moomoo SG (live link)
- Hidden for now:
  - Wise
  - IBKR

## Current structure
- `index.html` — homepage / offer directory
- `offers/trust-bank.html` — Trust detail page
- `offers/youtrip.html` — YouTrip detail page
- `offers/moomoo-sg.html` — Moomoo detail page
- `offers/offers.csv` — lightweight offer registry / maintenance sheet
- `style.css` — shared styles

## Content rules
- Every live offer should have:
  - clear reward summary
  - last-checked date
  - official terms or official support page
  - basic qualification explanation
- Do not use fake countdowns, fake urgency, or placeholder contact/social/newsletter blocks.
- For investing / brokerage offers, include a risk note.
- Prefer factual summaries over aggressive hype.

## Deployment notes
- Site is static HTML/CSS.
- Use relative internal links so GitHub Pages pathing remains stable.
- Before publish / refresh, quickly re-check live reward wording for each offer.

## Next likely work
- deploy-ready check / publish
- add more offers only if they are real, live, and easy to verify
- optional later lane: small AI affiliate section
