# chaluvadis.github.io

Personal engineering landing page for **Surendra Chaluvadi** — backend and platform engineer building secure cloud systems, developer tooling, and AI-ready infrastructure.

---

## What this site is

A recruiter-optimized, static landing page that communicates engineering identity in under 10 seconds. Designed as a modern engineering product page — not a resume, not a generic portfolio.

The page is the source of truth for:
- Who I am and what I build
- Featured open-source systems and tooling
- Skill groups organized by domain
- Links to GitHub and LinkedIn for direct contact

---

## Site sections

| Section | Purpose |
|---|---|
| **Hero** | Name, positioning, GitHub / LinkedIn CTAs |
| **Proof strip** | Compact row of career and output proof points |
| **About** | 2-paragraph engineering identity summary |
| **Featured Systems** | Curated repos — operators, security tooling, platform tools |
| **Skills** | Domain-grouped: Platform/Cloud, Security/Identity, Backend/Tooling, AI/Observability |
| **Engineering Artifacts** | Context on GitHub as an engineering artifact system |
| **Contact** | Role fit statement + direct CTA links |

---

## Customization

### `index.html`
All content lives directly in the HTML — no build step required. To update:
- **Hero tagline** — edit the `<p class="hero-tagline">` block
- **Proof strip numbers** — edit `<div class="proof-value">` values
- **Featured systems** — each `<div class="system-card">` is self-contained; add, remove, or edit cards directly
- **Skills** — each `<div class="skill-group">` block contains a `<ul class="skill-list">`
- **Contact message** — edit `<p class="contact-intro">`

### `styles.css`
Design tokens are defined as CSS custom properties in `:root` at the top of the file:

```css
:root {
  --bg:         #0b0f14;   /* page background */
  --surface:    #111820;   /* card / panel surface */
  --border:     #1e2d3d;   /* subtle borders */
  --text:       #e2e8f0;   /* primary text */
  --text-muted: #7a93a8;   /* secondary / label text */
  --accent:     #00c8ff;   /* cyan highlight / links */
}
```

Change any token to restyle the entire page.

---

## Deployment

The site deploys automatically via **GitHub Pages** from the `master` branch root. No build process — changes to `index.html` or `styles.css` go live on push.

Make sure GitHub Pages is configured to serve from: **Branch: `master` / Root (`/`)**

---

## Stack

- Plain HTML5 + CSS3 (no framework, no bundler)
- [JetBrains Mono](https://fonts.google.com/specimen/JetBrains+Mono) via Google Fonts
- Zero JavaScript — fully static, instant load

