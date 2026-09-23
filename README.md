# Disney Voice — Sustainment Developer Guide

Static HTML/CSS documentation for CCN MAUI Voice & Outbound Outreach sustainment developers.

**Live site:** Deploy to [Vercel](https://vercel.com) from this repo (see below).

## Quick Start

1. Open `index.html` in a browser.
2. Optional local server: `npx serve .` from this folder.
3. **Case Management:** `modules/case-management/overview.html`
4. **Component map:** `modules/case-management/component-map.html`
5. **Omni routing:** `modules/case-management/omni-routing.html`
6. **Home Dashboard:** `modules/home-dashboard/overview.html`

## Deploy to Vercel

1. Push this repo to GitHub: `https://github.com/karanyede/Disney-Voice`
2. In [Vercel](https://vercel.com/new), import the **Disney-Voice** repository.
3. Use defaults:
   - **Framework Preset:** Other (static site)
   - **Root Directory:** `.` (repository root)
   - **Build Command:** leave empty
   - **Output Directory:** leave empty (or `.`)
4. Deploy. Vercel serves `index.html` at the site root.

`vercel.json` is included for clean URLs.

## Structure

```
├── index.html
├── vercel.json
├── docs/
│   ├── case-management-architecture.md
│   └── case-management-design-decisions.md
├── assets/css/site.css
├── assets/js/nav.js
└── modules/
    ├── case-management/
    ├── home-dashboard/
    ├── architecture/
    ├── frameworks/
    ├── reference/
    ├── outbound/
    ├── voice/
    ├── integrations/
    └── widgets/
```

## Salesforce Source

Code references point to: `WDW R2 Latest/force-app/main/default`

## Confluence

[WDWCCN Space](https://disneyexperiences.atlassian.net/wiki/spaces/WDWCCN/overview)
