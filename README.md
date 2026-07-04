# Sabbir · Portfolio

Awwwards-style one-page developer portfolio for **Sabbir ([darkksabbir](https://github.com/darkksabbir))**. Static site, no build step. Design polished with the [ui-ux-pro-max](https://github.com/nextlevelbuilder/ui-ux-pro-max-skill) design system (Motion-Driven style, Trust Blue palette).

## Run it

```bash
python3 -m http.server 8000
# open http://localhost:8000
```

Any static server works.

## What's inside

| Path | Purpose |
| --- | --- |
| `index.html` | The home page (hero, tech marquee, work, about, stack, philosophy, contact) |
| `css/tokens.css` | Design tokens: Trust Blue palette, type scale, spacing, motion |
| `css/main.css` | Components, all reading from tokens (+ scroll progress, tech pills, monogram) |
| `js/fluid.js` | three.js fluid shader hero (domain-warped fbm, pointer-reactive) |
| `js/main.js` | GSAP ScrollTrigger choreography + scroll progress bar |
| `js/theme.js` | Light (default) / dark toggle, persisted |
| `vendor/` | Self-hosted three.js, GSAP, ScrollTrigger, Phosphor Icons |
| `assets/fonts/` | Self-hosted Inter and Space Grotesk (variable, latin subset) |
| `DESIGN-SYSTEM.md` | System documentation |

## Content notes

Some content is **placeholder** pending real details. Swap these in when ready:

- **Projects 02–04** ("Realtime Dashboard", "Commerce API", "Component Library") are representative examples — replace with real repos/case studies. Project 01 (`upp`) links to the real GitHub repo.
- **Stats** (projects shipped, years, technologies) are placeholder numbers.
- **Email** `hello@darkksabbir.dev` is a placeholder — update to a real address.
- **GitHub** and **LinkedIn** links point to the real `darkksabbir` profiles.
- The portrait is a stylized "S" monogram rather than a photo — drop in a headshot if preferred.

## Notes

- Photography is hot-linked from Unsplash (free license); everything else is self-hosted, so the page works offline apart from photos.
- Respects `prefers-reduced-motion` throughout.
