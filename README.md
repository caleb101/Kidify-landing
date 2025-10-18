# Kidify Landing Page (Netlify-ready)

This repository contains a lean, mobile-first landing page for **Kidify** — a gamified discipline & digital-wellness app for kids (ages 5–16). The page is designed to validate demand, capture waitlist signups via Netlify Forms, and showcase a lightweight interactive demo.

## What's included
- `index.html` — main landing page (Tailwind CDN, Netlify form)
- `assets/` — placeholder for images (add your own `og-image.png` here)
- `README.md` — this file

## Quick start (deploy to Netlify)
1. Create a GitHub repository and push this folder (`kidify-landing`) to it.
2. In Netlify, select **New site from Git** and connect your GitHub repo.
3. No build command needed for static HTML — deploy directly.
4. After deploy, go to **Site settings → Forms** to view waitlist submissions.

## Netlify forms
The waitlist form uses Netlify Forms. Form submission data will appear in your Netlify dashboard once the site is live. You can export submissions as CSV or connect to Zapier/Mailchimp for automated workflows.

## Customization
- Replace `assets/og-image.png` with a shareable social image (recommended 1200x630).
- Update contact email in the footer (`calebemales@gmail.com`).
- Add Google Analytics / Meta Pixel snippets where indicated in `index.html` if you want tracking.

## Design choices
- **Color palette:** Indigo primary (#4F46E5) + Green accent (#22C55E) for trust, growth and optimism.
- **Typography:** Poppins and Inter (system fallback used in HTML).

## Next steps
- Connect form submissions to Mailchimp or a CRM.
- Add domain (`kidifyapp.com`) in Netlify settings and configure DNS.
- Consider compiling Tailwind for production to reduce CSS size.

---
Built by Caleb Enya — feel free to edit and iterate.
