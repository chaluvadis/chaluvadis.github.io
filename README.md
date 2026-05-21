# chaluvadis.github.io

Static personal landing page for **Surendra Chaluvadi** — backend and platform engineer building secure cloud systems, developer tooling, and AI-ready infrastructure.

## Design direction

This version keeps the recruiter-first structure but shifts the visual system to a warmer, calmer dark theme:

- Deep espresso / charcoal backgrounds
- Warm sand surfaces and softer borders
- Amber / muted gold accents
- JetBrains Mono used with more spacing, contrast, and softer card treatment

## Site structure

- **Hero** — positioning, CTA, and current focus
- **Proof strip** — fast credibility scan
- **About** — concise engineering summary
- **Featured Systems** — strongest platform, security, and tooling projects
- **Skills** — grouped by systems domain
- **Engineering Artifacts** — GitHub context and snapshot
- **Contact** — role fit and direct links

## Customization

### `index.html`
Edit content directly in the markup. The main customization points are:

- hero copy and focus list
- proof items
- featured system cards
- skills groups
- GitHub snapshot rows
- contact copy

### `styles.css`
The site is driven by CSS tokens in `:root`. The most important ones are:

```css
:root {
  --bg: #1a1411;
  --surface: rgba(43, 33, 28, 0.88);
  --border: rgba(214, 186, 158, 0.18);
  --text: #f5ede4;
  --text-muted: #c8b8a7;
  --accent: #d8a66c;
}
```

Adjust these tokens first to retheme the full page. Surface radius, shadows, and layout width are also centralized near the top of the file.

## Deployment

GitHub Pages serves the site from the `master` branch root. There is no build step — updating `index.html` or `styles.css` is enough.

## Stack

- Plain HTML5 + CSS3
- [JetBrains Mono](https://fonts.google.com/specimen/JetBrains+Mono) via Google Fonts
- Zero JavaScript
