# Frontend Assignment (React + Vite + Tailwind)

A production-ready, responsive implementation scaffold to translate a Figma design into code quickly and cleanly.

## Live Demo

Deploy first, then paste your link here (e.g., https://frontend-assignment-yourname.vercel.app).

## Tech Stack

- **React 18** + **Vite 5** (fast dev + optimized builds)
- **Tailwind CSS 3** for styling & design tokens
- **Framer Motion** for subtle motion
- Semantic HTML, accessible controls, mobile-first

## How to Run Locally

```bash
npm install
npm run dev
```

## Build

```bash
npm run build
npm run preview
```

## Project Structure

```
src/
  assets/           # SVGs and placeholders
  components/       # UI components
  App.jsx           # Page composition
  index.css         # Tailwind + CSS variables
  main.jsx          # React entry
tailwind.config.cjs
postcss.config.cjs
vite.config.js
index.html
```

## Design Tokens & Theming

All key colors are mapped to CSS variables (see `src/index.css`) and wired to Tailwind theme in `tailwind.config.cjs`.  
When you inspect values in Figma, simply replace the `--primary`, `--foreground`, etc.

## What to Customize to Match Figma

- **Fonts**: change the Google Fonts `<link>` in `index.html`.
- **Colors**: update CSS variables in `src/index.css`.
- **Spacing & sizes**: tweak Tailwind classes per component.
- **Images/Icons**: replace SVG placeholders in `src/assets`.
- **Copy**: update headings and text to match the design.

## Accessibility Checklist

- Buttons have visible focus states (inherited via Tailwind).
- Interactive elements use semantic tags and `aria-label`s where needed.
- Sufficient color contrast: ensure your final palette meets WCAG AA.

## Deployment (Vercel)

1. Push this repository to GitHub.
2. Import the repo in **Vercel**.
3. Framework preset: **Vite**.
4. Build command: `npm run build`
5. Output directory: `dist`
6. **Deploy** -> copy the live URL.

Alternatively, use **Netlify** (build: `npm run build`, publish: `dist`).

## Notes on Fidelity

This scaffold is intentionally clean and modular so you can quickly map Figma layers to components:
- `Navbar` → header & navigation
- `Hero` → top section with headline & visual
- `Features` → cards grid
- `Testimonials` → quotes grid
- `Pricing` → tier cards
- `CTA` → call-to-action card
- `Footer` → site footer

## Author & Credits

Created by Your Name for the Frontend Developer Intern assignment.
