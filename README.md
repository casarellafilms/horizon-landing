# HORIZON — Landing Page

AI-Native Business Consulting, built for the American market. A single, self-contained landing page for **HORIZON** — positioning the "AI Brain" as the intelligence layer that runs a company's sales, marketing, content and operations.

## Overview

- **Single file:** `index.html` — no build step, no dependencies, no framework. All CSS and JS are inline; only Google Fonts (Cormorant Garamond + Space Grotesk) load externally.
- **Design source:** compiled faithfully from a [Claude Design](https://claude.ai/design) `.dc.html` project into standalone HTML/CSS/vanilla JS (proprietary runtime replaced with a self-contained script).
- **Motion:** animated starfield canvas, scroll-reveal (IntersectionObserver), parallax, count-up, glass cards with cursor spotlight, scroll progress bar, sticky nav, modal, and a mobile menu.
- **Responsive:** verified with zero horizontal overflow from 320px to 1440px+; nav collapses to a hamburger menu on small screens.

## Local preview

```bash
python3 -m http.server 8000
# open http://localhost:8000
```

## Deploy

Hosted on **Vercel** as a static site (`vercel.json` adds clean URLs + security headers). Any push to `main` triggers a production deploy.

## Before going live (client TODO)

- Replace the placeholder contact `hello@horizon.ai` and social links.
- Wire the "Book a diagnosis" email capture to a real form endpoint / CRM.
- Add a real Open Graph share image and final domain in the canonical/OG tags.

---
© 2026 HORIZON. Built for the American market.
