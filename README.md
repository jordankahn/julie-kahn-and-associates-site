# Julie Kahn & Associates — Website

Single-page marketing website for Julie Kahn & Associates Speech Language Pathology Services, based in Highland Park, IL.

## Structure

```
julie-kahn-website/
├── index.html       # Entire site (HTML + CSS + JS, fully self-contained)
├── logo.png         # Full color logo with text
├── logo copy.png    # Icon-only logo (used as favicon)
└── README.md
```

## Sections

- **Header** — Sticky nav with logo text, smooth-scroll links, and phone CTA
- **Hero** — Full-height banner with contact info strip
- **About** — Practice intro with photo and key highlights
- **Services** — 8 service cards (social skills, articulation, language, emotional regulation, peer groups, parent coaching, adult services, school collaboration)
- **Team** — Julie Kahn + Michelle therapist cards
- **Process** — 4-step intake flow
- **Testimonials** — Auto-advancing carousel (2 visible), swipe + keyboard accessible
- **Contact** — Form + address/phone/email
- **Footer** — Nav links, contact info, full-color logo

## Design

- **Font:** Lora (headings) + Inter (body) via Google Fonts
- **Icons:** Font Awesome 6.5 via CDN
- **Color palette:** Lavender-purple primary (`#6B45A8`) with logo accent colors (teal `#55C8C4`, green `#7BBF35`, blue `#59B8D4`)
- **No build step** — open `index.html` directly in a browser

## Contact Info

- **Phone:** (847) 212-3765
- **Email:** juliekslp@gmail.com
- **Address:** 480 Elm Place, Suite 105B, Highland Park, IL 60035

## Before Deploying

- [ ] Wire up the contact form (recommend [Netlify Forms](https://docs.netlify.com/forms/setup/) or [Formspree](https://formspree.io))
- [ ] Update `<link rel="canonical">` and `og:url` meta tags with the real domain
- [ ] Replace image URLs in `index.html` that still point to `dev5.myvtd.site` with locally hosted photos
- [ ] Add real social media profile URLs in the footer
