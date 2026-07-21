# Brian's Consulting — Website

Static marketing site for Brian's Consulting (Madison, WI).

## Pages
- `index.html` — **Home:** AI Growth System for Local Businesses ($297/mo Core Growth, $397/mo Complete AI Acceleration).
- `real-estate.html` — 24/7 AI Inbound Receptionist for Real Estate ($297/mo).

Each page is a single self-contained file (inline CSS + vanilla JS), and the two are cross-linked.

## Stripe checkout
The homepage's Get Started buttons and signup form redirect to Stripe Payment Links.
Paste your two **recurring** Payment Link URLs into the `STRIPE_LINKS` object near the top of the `<script>` in `index.html` (Core = $297/mo, Complete = $397/mo).

## Hosting
Deployed with GitHub Pages — Settings → Pages → Deploy from a branch → `main` / root.
