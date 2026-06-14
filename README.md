# Ajith E — Portfolio

A React + Vite portfolio site styled around a code-editor / terminal aesthetic.

## Getting started

```bash
npm install
npm run dev      # local dev server
npm run build    # production build -> dist/
npm run preview  # preview the production build
```

## Adding your resume

Drop your resume PDF into the `public/` folder as `Ajith_E_Resume.pdf` —
the "resume.pdf" button in the nav links to `/Ajith_E_Resume.pdf`.

## Deploying

The `dist/` folder after `npm run build` is a static site — deploy it to
Vercel, Netlify, GitHub Pages, or any static host.

For GitHub Pages, set `base: '/your-repo-name/'` in `vite.config.js` before building.

## Structure

```
src/
  components/   one component + CSS module per section
  App.jsx        page composition
  index.css      design tokens & global styles
public/
  favicon.svg
```
