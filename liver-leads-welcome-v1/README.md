# Liver Leads Welcome Flow V1

This folder translates the six PRD tabs into standalone Klaviyo-compatible HTML email drafts using the existing Dose module library in this repository.

## Mapping

1. `01_perceived-value.html` — Perceived Value / full value stack
2. `02_clinical-proof.html` — Clinical Proof / strongest approved result
3. `03_why-dose.html` — Product Differentiation / Dose vs supplement stack
4. `04_customer-proof.html` — Customer Proof / UGC + community stories
5. `05_appeal-to-authority.html` — Expert / authority validation
6. `06_final-close.html` — Final Close / offer + urgency

## Existing repo modules reused conceptually

- 01 core logo header
- 03 hero image + headline + CTA
- 05 two-column image + text
- 07 closing CTA banner
- 09 legal / claims footer
- 22 doctor / expert quote
- 23 clinical proof / study callout
- 51 product comparison
- 60 customer testimonial
- 61 star-rating / review
- 63 UGC photo
- 64 community quote
- 65 expert endorsement

## Production notes

All placeholders prefixed with `REPLACE_WITH_` need final production values.
Clinical claims, customer metrics, expert quotes, and testimonials must use approved language.
The emails intentionally keep a 600px table-based structure, inline-friendly styles, mobile stacking, clear CTA hierarchy, and Dose Warm Science colors.
