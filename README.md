# medolinshajeena.design

The source for my interactive portfolio & resume — live at **[medolinshajeena.design](https://medolinshajeena.design)**.

I'm Medolin Shajeena, a UX/UI designer. I designed this site in Figma and hand-coded it in vanilla HTML, CSS, and JavaScript — no frameworks, no build step — to show the front-end fundamentals behind my design work. The entire site is one file: `index.html`.

## What's inside

**Dynamic color system (Material You–inspired).**
Pick any seed swatch in the top bar and the whole site re-themes live: primary and container roles, tonal surfaces, and text colors are all generated from a single hue, in both light and dark mode. It's the same tokens-first thinking I bring to product design systems — define the system once, and every screen stays consistent.

**Runtime accessibility guard.**
Accessible should mean provable. Every generated palette is contrast-checked at runtime using the WCAG relative-luminance formula, and the primary tone is automatically adjusted until button text and links pass **WCAG AA (≥ 4.5:1)** — for any seed, in either mode. Try the teal seed and watch the link color deepen to comply.

**Accessible by construction.**
Skip-to-content link, visible keyboard focus everywhere, full ARIA tabs pattern with arrow-key navigation, `aria-live` announcements for dynamic content, `prefers-reduced-motion` and `prefers-color-scheme` respected, and a static fallback palette so the site is fully styled even with JavaScript disabled.

**Design details.**
Tonal-surface depth instead of heavy shadows, corner-radius morphing on hover, a rotating Material "cookie" monogram, and live component specimens (buttons, chips, switches, tone ramps) rendered from the active palette.

## Structure

| File | Purpose |
|---|---|
| `index.html` | The entire site — markup, styles, and scripts |
| `og-image.png` | Social preview card (OpenGraph / Twitter) |
| `Medolin-Shajeena-Resume.pdf` | Downloadable resume |
| `CNAME` | Custom domain configuration for GitHub Pages |

## Elsewhere

- **Case studies:** [behance.net/medolinshajeena1218](https://www.behance.net/medolinshajeena1218)
- **LinkedIn:** [linkedin.com/in/medolin-shajeena-b97321108](https://www.linkedin.com/in/medolin-shajeena-b97321108)
- **Email:** shajimartin10@gmail.com

---

© Medolin Shajeena. Design and code by me. Feel free to read and learn from the source — please don't republish it as your own.
