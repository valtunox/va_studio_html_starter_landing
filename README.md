<p align="center">
  <img src="https://img.shields.io/badge/HTML-5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5" />
  <img src="https://img.shields.io/badge/CSS-3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3" />
  <img src="https://img.shields.io/badge/Zero_Build-Zero_Deps-22C55E?style=for-the-badge" alt="Zero build" />
  <img src="https://img.shields.io/badge/Studio_Builder-Ready-8B5CF6?style=for-the-badge" alt="Studio Builder Ready" />
  <img src="https://img.shields.io/badge/AI-Ready-F59E0B?style=for-the-badge" alt="AI Ready" />
</p>

<h1 align="center">VA Studio HTML Starter — Landing Page</h1>

<p align="center">
  <strong>A full-length B2B SaaS marketing landing page in pure HTML + CSS.</strong>
</p>

<p align="center">
  Sticky nav, hero with floating stat card, logo cloud, 6-feature grid,<br/>
  split-feature block, testimonials, 3-tier pricing, dark CTA banner, and a 4-column footer.
</p>

<p align="center">
  <a href="#quick-start">Quick Start</a> &bull;
  <a href="#sections">Sections</a> &bull;
  <a href="#studio-builder-integration">Studio Integration</a> &bull;
  <a href="#customizing">Customizing</a>
</p>

---

## Quick Start

```bash
python -m http.server 8000
# or
npx serve .
```

Open [http://localhost:8000](http://localhost:8000).

## Sections

1. **Sticky navbar** — brand, 5 section links, sign-in + primary CTA, blurred backdrop on scroll
2. **Hero** — announcement pill, Playfair Display headline with italic accent word, subtitle, two CTAs, hero visual with a floating "MRR +18.4%" stat card
3. **Logo cloud** — 6 company wordmarks with hover lift
4. **Section head** — eyebrow, headline, lead copy
5. **6-feature grid** — color-coded icon tiles (blue, green, amber, violet, rose, slate), link arrows
6. **Split feature** — 50/50 image + copy block with a checkmark list and outline CTA
7. **Testimonials** — 3 quote cards with pravatar avatars and roles
8. **Pricing** — Starter / Growth (featured) / Enterprise with hover lift
9. **CTA banner** — dark gradient block with two buttons
10. **Footer** — 4-column link grid, legal row, cookie links

## Studio Builder Integration

- Every major section has an `id` (`#product`, `#solutions`, `#customers`, `#pricing`) so Studio can deep-link
- Content arrays are presented as semantic lists — Studio AI can duplicate/reorder cards safely
- Unsplash + pravatar URLs use stable photo IDs — easy to swap for Studio-hosted assets
- Typography pairs (Inter for body, Playfair Display for display) match the VA Studio design-system defaults

## Tech Stack

| Layer | Technology |
|-------|-----------|
| **Markup** | HTML5, semantic landmarks, ARIA |
| **Styling** | CSS3 custom properties, responsive grid + flex |
| **Fonts** | Inter + Playfair Display (Google Fonts) |
| **Images** | Unsplash hero, pravatar avatars |
| **Icons** | Inline SVG (check, play, arrow) |

## Project Structure

```
va_studio_html_starter_landing/
├── index.html      # Full landing page
├── styles.css      # Design tokens + responsive breakpoints
└── README.md
```

## Customizing

- **Brand:** wordmark + mark in the nav and footer — both are inline SVG
- **Hero image:** swap the Unsplash URL in `.visual-card`
- **Feature icons:** inline SVGs in each `.feature-icon` block — replace with your own
- **Pricing:** edit the 3 `.price-card` blocks — `featured` class controls the highlighted tier
- **Colors:** update CSS vars at the top of `styles.css` (`--accent`, `--success`, `--violet`, `--rose`)

## License

MIT

---

<p align="center">
  Part of the <strong>VA Studio</strong> starter family · Built for rapid prototyping with an AI copilot.
</p>
