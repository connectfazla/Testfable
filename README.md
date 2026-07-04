# Fazla Rabbi · Portfolio

Awwwards-style one-page portfolio for **Fazla Rabbi** — a project manager and web developer with 6+ years leading cross-functional teams for international clients. Static site, no build step. Design polished with the [ui-ux-pro-max](https://github.com/nextlevelbuilder/ui-ux-pro-max-skill) design system (Motion-Driven style, Trust Blue palette).

## Run it

```bash
python3 -m http.server 8000
# open http://localhost:8000
```

Any static server works.

## What's inside

| Path | Purpose |
| --- | --- |
| `index.html` | The home page (hero, skills marquee, experience, about, stack, philosophy, contact) |
| `css/tokens.css` | Design tokens: Trust Blue palette, type scale, spacing, motion |
| `css/main.css` | Components, all reading from tokens (+ experience, scroll progress, tech pills, monogram) |
| `js/fluid.js` | three.js fluid shader hero (domain-warped fbm, pointer-reactive) |
| `js/main.js` | GSAP ScrollTrigger choreography + scroll progress bar |
| `js/theme.js` | Light (default) / dark toggle, persisted |
| `vendor/` | Self-hosted three.js, GSAP, ScrollTrigger, Phosphor Icons |
| `assets/fonts/` | Self-hosted Inter and Space Grotesk (variable, latin subset) |
| `DESIGN-SYSTEM.md` | System documentation |

## Content

All content is real, sourced from Fazla Rabbi's CV:

- **Experience** — Middle Manager & Project Manager at UPPEARANCE (Dubai, remote), and freelance UX/web work via Upwork.
- **Stats** — 6+ years, 50+ websites delivered, 100% client satisfaction.
- **Contact** — email `connectfazla@gmail.com`, phone, website `fazla.dev`, and LinkedIn (`darkksabbir`).
- The portrait is a stylized "F" monogram; drop in a headshot if preferred.

## Notes

- The page is fully self-hosted (fonts, JS, icons) and works offline — no external images.
- Respects `prefers-reduced-motion` throughout.
