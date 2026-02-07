# Formfit – Frontend Crash Course Project

Production-ready responsive website generated from the Figma design (2026 Frontend Crash Course Project – Community).

## Stack

- **HTML5** – Semantic structure
- **Tailwind CSS** (CDN) – Layout and styling with custom theme (Manrope, Figma colors, breakpoints)
- **Vanilla JS** – Smooth scroll for anchor links

## Design match

- **Colors:** `#191A20` (bg), `#1F80FF` (primary), `#AEB1C2` (muted), `#484B59` (border), `#FFFFFF` (text)
- **Typography:** Manrope 400/700 from Google Fonts; sizes 18px (nav), 20px (subhead/CTA), 28px (features), 40px (card), 66px (headline)
- **Gradients:** Hero backdrop and app card gradient from Figma
- **Spacing:** 24px (headline block), 48px (CTA block), 135px horizontal padding at 1440px+
- **Breakpoints:** 320px, 768px, 1024px, 1440px (Tailwind: `xs`, `sm`, `md`, `lg`)

## Run locally

Open `index.html` in a browser, or use a local server:

```bash
npx serve .
# or
python -m http.server 8080
```

Then open `http://localhost:8080` (or the URL shown).

## Assets

- `assets/images/hero-image.png` – Hero section image (from Figma)
- `assets/images/girl-sitting-4f7c0e.png` – Lower section image (from Figma)
- Avatar placeholders use DiceBear; hero/girl images have Unsplash fallbacks if files are missing.

## Responsive behavior

- **320px:** Single column, compact nav, stacked CTAs, in-flow phone card
- **768px:** Larger type, side-by-side CTAs, same in-flow card
- **1024px:** Absolute phone card over hero, hero image visible on the right
- **1440px+:** Full Figma layout with 135px horizontal padding
