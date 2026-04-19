# Singapore Referrals

Small static referral site for Singapore-facing sign-up bonuses and invite offers.

## Current live offers
- Trust Bank
- YouTrip
- Moomoo SG

## Structure
- `index.html` — homepage
- `offers/` — per-offer detail pages
- `offers/offers.csv` — lightweight offer registry
- `style.css` — shared styles
- `context.md` — project operating context

## Editing rules
- Keep only real, live offers on the homepage.
- Every live offer should have:
  - a last-checked date
  - official terms/support link
  - a simple explanation of how to qualify
- Hidden or paused offers should stay in `offers/offers.csv` until ready.

## Publish checklist
1. Re-check each live offer’s official terms page.
2. Confirm referral links / codes still work.
3. Update `last checked` if needed.
4. Verify internal links still resolve.
5. Push to the Pages repo.

## Notes
- This project intentionally avoids fake urgency, giant coupon-dump behavior, and placeholder blocks that hurt trust.
- For investment-related offers, keep risk notes visible.
