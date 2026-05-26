# chaluvadis.github.io

Personal site for **Surendra Chaluvadi** — a platform and backend engineer building secure cloud systems, developer tooling, and AI-safe engineering workflows.

---

## What this site is

A recruiter-first engineering landing page designed to communicate identity, systems focus, and technical direction in under 10 seconds.

This site is intentionally built as:
- a **product-style engineering brand page**
- not a resume
- not a generic portfolio
- not a blog

It acts as the public entry point for:
- platform and backend positioning
- selected GitHub systems and tooling
- core engineering strengths
- direct GitHub and LinkedIn navigation

---

## Site sections

| Section | Purpose |
|---|---|
| **Hero** | Clear identity, positioning, and primary calls to action |
| **Proof strip** | Fast recruiter-readable proof of experience and focus |
| **About** | Short explanation of engineering scope and systems mindset |
| **Featured Systems** | Curated repositories that best represent platform, backend, and tooling work |
| **Skills** | Grouped by systems built, not keyword stuffing |
| **GitHub as Artifact System** | Explains how repositories reflect engineering quality and leverage |
| **Contact** | Clear CTA for hiring or professional outreach |

---

## Design direction

The visual system is designed to feel:
- modern
- minimal
- technical
- calm
- recruiter-readable

### Design principles
- dark-first interface
- JetBrains Mono typography
- high whitespace
- subtle card surfaces
- soft contrast
- warm premium palette
- no unnecessary animation
- fully static and maintainable

### Core style tokens

```css
:root {
  --bg:        #15110f;
  --surface:   #1d1714;
  --surface-2: #241d19;
  --border:    rgba(215, 155, 91, 0.18);
  --text:      #f4e9dc;
  --muted:     #b9a897;
  --accent:    #d79b5b;
  --accent-2:  #e7bf8b;
}
```

These tokens are defined in `styles.css` and can be adjusted to restyle the entire site.

---

## Customization

### `index.html`
All site content lives directly in the HTML. No build step is required.

Most common edits:
- **Hero positioning** — update headline and intro copy
- **Proof strip** — adjust experience / focus statements
- **Featured Systems** — update project cards and repository links
- **Skills** — revise grouped capabilities based on current focus
- **Contact section** — update outreach message or CTA links

### `styles.css`
Use `styles.css` to adjust:
- color tokens
- spacing
- card surfaces
- typography rhythm
- layout responsiveness

The page is intentionally simple so future edits can happen quickly without a framework or bundler.

---

## Deployment

The site deploys through **GitHub Pages** from the repository root on the `master` branch.

### Expected setup
- **Branch:** `master`
- **Folder:** `/ (root)`

Because the site is plain HTML and CSS, changes go live directly when pushed.

---

## Stack

- HTML5
- CSS3
- JetBrains Mono via Google Fonts
- No framework
- No bundler
- No JavaScript required for core rendering

---

## Content strategy

This site is optimized around one idea:

> GitHub is the engineering artifact system.  
> The website is the recruiter-facing summary layer.

That means the page should stay:
- concise
- curated
- proof-driven
- aligned with the strongest repositories only

---

## Recommended adjacent updates

For best results, align this site with:
- GitHub profile bio
- pinned repositories
- GitHub profile README
- LinkedIn headline and About section

Suggested positioning line:

**Platform and backend engineer building secure cloud systems, developer tooling, and AI-safe engineering workflows.**
