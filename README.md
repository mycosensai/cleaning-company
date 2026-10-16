# Sparkling Cleaning Services

A single-page static website for Sparkling Cleaning Services — residential house cleaning.

**Live:** https://mycosensai.github.io/cleaning-company/ (page2: [/page2.html](https://mycosensai.github.io/cleaning-company/page2.html))

## Fidelity

**Lo-fi structure** — single HTML file, no build step, no dependencies beyond Google Fonts CDN.

## Tech Stack

- HTML5, CSS3, vanilla JavaScript
- Google Fonts: Bodoni Moda (display), Manrope (body)
- No frameworks, no bundlers

## Design Tokens

| Token | Value | Usage |
|-------|-------|-------|
| `--bg-dark` | `#081828` | Header, services, quote sections |
| `--bg-black` | `#010101` | Footer, booking modal |
| `--bg-light` | `#f5f0e8` | Pricing, process, tagline sections |
| `--gold` | `#b2884e` | Prices, CTAs, accents |
| `--gold-lt` | `#f9e7b7` | Headings, highlights on dark |
| `--gold-deep` | `#4b3116` | Borders, dividers |
| `--teal` | `#446e81` | Links, hover states |
| `--text-dark` | `#1a1a1a` | Body text on light |
| `--text-light` | `#f2efe8` | Body text on dark |
| `--text-soft` | `#8a9a9a` | Muted text (≥4.5:1 on dark) |

## Typography

- **Display/headings:** Bodoni Moda (serif, weight 400)
- **Body/UI:** Manrope (sans-serif, weight 300–700)

## Sections

1. **Header** — sticky nav, brand mark, CTA button
2. **Hero** — dark navy, gold serif headline, trust indicators
3. **Pricing** — light cream, 4 price cards, 2 add-on cards
4. **Services** — dark navy, 4 service cards with icons
5. **How It Works** — light, 4 steps with Roman numerals
6. **Quote Form** — dark, 2-column layout with form
7. **Tagline** — light, centered italic serif
8. **Footer** — black, brand + links
9. **Booking Widget** — fixed FAB + modal with date/time selection

## Interactions

- Smooth scroll navigation
- Hover states on cards, buttons, links
- Booking modal: date/time chip selection, summary display, form validation
- Quote form: client-side validation, mailto fallback
- Escape key closes booking modal
- Backdrop click closes booking modal

## Pricing

| Home Size | Starting Price |
|-----------|---------------|
| 1-Bedroom | $80 – $100 |
| 2-Bedroom | $100 – $150 |
| 3-Bedroom | $150 – $175 |
| 4-Bedroom | $175 – $220 |

**Add-ons:**
- Deep Clean: +$50 to +$100 depending on condition
- Move-Out Cleans: higher rates due to extra time and detail

*Prices may increase based on home size, condition, number of bathrooms, pets, and requested add-ons.*

## Deployment

Open `index.html` directly in a browser, or serve with any static file server:

```bash
python -m http.server 8080
```

## License

© 2026 Sparkling Cleaning Services. All rights reserved.
