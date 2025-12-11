# Pineapple Design Tokens

Shared design system for the Heat Shock Pineapple sites.

This package is the **single source of truth** for:

- Colors and surfaces (paper, surface, deep card colors)
- Typography (Jost, serif stack, mono stack)
- Layout tokens (border radius, max-width, breakpoints)
- Base theme styles (body, headings, ambient “glow” background)

It is consumed by multiple Astro sites:

- `hub` – main landing page (`heatshockpineapple.com`)
- `portfolio` – projects and case studies
- `photos` – photography-focused site
- `blog` – long-form writing

Each site imports these styles instead of copying CSS between repos.

---

## Installation

Install via GitHub in each site repo:

```bash
npm install github:JaRoHe318/pineapple-design-tokens