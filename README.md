# Julie Kahn & Associates — Website

Single-page marketing website for Julie Kahn & Associates Speech Language Pathology Services, based in Highland Park, IL.

## Structure

```
julie-kahn-website/
├── index.html            # Entire site (HTML + CSS + JS, fully self-contained)
├── logo.png              # Full color logo with text (used in footer)
├── logo copy.png         # Icon-only logo (used as favicon)
├── images/               # All site images (team photos, hero carousel, content)
│   ├── social-preview.png  # 1200×630 OG/iMessage share preview
│   └── ...
├── CLAUDE.md             # Technical reference for AI-assisted development
└── README.md
```

## Sections

- **Header** — Sticky nav with logo text, smooth-scroll links, and phone CTA
- **Hero** — Two-column layout: text/CTAs left, 3-photo crossfade carousel right
- **About** — Practice intro with photo and key highlights
- **Services** — 8 service cards with logo accent colors (social skills, articulation, language, emotional regulation, peer groups, parent coaching, adult services, school collaboration)
- **Team** — All 7 therapists with photos, credentials, and bios
- **Process** — 4-step intake flow
- **Testimonials** — Auto-advancing carousel (2 visible), swipe + keyboard accessible
- **Contact** — Form + address/phone/email
- **Footer** — Nav links, contact info, full-color logo

## Design

- **Font:** Lora (headings) + Inter (body) via Google Fonts
- **Icons:** Font Awesome 6.5 via CDN
- **Primary color:** `#6B45A8` (purple)
- **Accent colors from logo:** teal `#55C8C4`, green `#7BBF35`, blue `#59B8D4`
- **ADA compliant:** all text colors meet WCAG AA contrast (4.5:1 minimum)
- **No build step** — open `index.html` directly in a browser

## Team

| Name | Credentials |
|---|---|
| Julie Kahn | M.A., CCC-SLP — Founder |
| Caryn Sachs Burstein | M.S., CCC-SLP |
| Michelle Pessis | M.S., CCC-SLP |
| Kylie Mowinski | M.S., CCC-SLP |
| Amanda Schatz | M.S., CCC-SLP |
| Rebecca Waxman | M.S., CCC-SLP |
| Tiffany Jacob | M.S., CCC-SLP |

## Contact Info

- **Phone:** (847) 212-3765
- **Email:** juliekslp@gmail.com
- **Address:** 480 Elm Place, Suite 105B, Highland Park, IL 60035

## Before Deploying

- [ ] Wire up the contact form (recommend [Netlify Forms](https://docs.netlify.com/forms/setup/) or [Formspree](https://formspree.io))
- [ ] Update `<link rel="canonical">` and `og:url` meta tags with the real domain
- [ ] Add real social media profile URLs in the footer
- [ ] Get a replacement photo for Rebecca Waxman (original was a broken file)
