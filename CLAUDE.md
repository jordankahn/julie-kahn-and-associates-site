# CLAUDE.md — Julie Kahn & Associates Website

## Project overview

Single-page static website (`index.html`) for a speech-language pathology private practice. No framework, no build step. All HTML, CSS, and JS live in one file.

## Key facts

- **Client:** Julie Kahn & Associates, Highland Park IL
- **Phone:** (847) 212-3765 | **Email:** juliekslp@gmail.com
- **Address:** 480 Elm Place, Suite 105B, Highland Park, IL 60035
- **Staff:** Julie Kahn (founder/SLP) and Michelle (SLP)

## Color palette

| Variable          | Hex       | Usage                          |
|-------------------|-----------|--------------------------------|
| `--teal`          | `#6B45A8` | Primary purple — buttons, links, accents |
| `--teal-dark`     | `#4A2D7A` | Hover states                   |
| `--teal-light`    | `#EDE5F5` | Light purple backgrounds       |
| `--amber`         | `#A85070` | Rose-mauve CTA accent          |
| `--logo-teal`     | `#55C8C4` | Logo accent — teal             |
| `--logo-green`    | `#7BBF35` | Logo accent — green            |
| `--logo-blue`     | `#59B8D4` | Logo accent — blue             |

All text colors pass WCAG AA contrast (4.5:1) on their respective backgrounds.

## Logo files

- `logo.png` — full color logo with text, used in footer (needs white bg container on dark surfaces)
- `logo copy.png` — icon-only version, used as favicon

## Testimonial carousel

- Located in `#testimonials` section
- Shows 2 cards at a time on desktop, 1 on mobile (< 768px)
- Card widths are set by JS on init and resize (`getVisible()` function)
- Auto-advances every 6 seconds, pauses on hover
- Supports touch swipe and keyboard arrow keys

## Contact form

The form is currently front-end only — no backend. To enable submissions, integrate Netlify Forms (add `netlify` attribute to `<form>`) or Formspree.

## Images

Photos currently load from `dev5.myvtd.site` (expired SSL cert). Replace with locally hosted files before going live.
