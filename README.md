# Beavo — landing page

Landing page for Beavo ("Escova comigo?"), in pt-BR. HTML + CSS, built with [Vite](https://vite.dev).

## Run locally

```bash
npm install
npm run dev
```

Then open the URL Vite prints (http://localhost:5173 by default).

## Build

```bash
npm run build     # outputs to dist/
npm run preview   # serves dist/ locally
```

## Files

- `index.html` — page markup (pt-BR), Vite entry point.
- `src/styles.css` — styles; colours, type, radii and shadows come from the Beavo design system tokens (see `:root`).
- `public/favicon.svg` — placeholder favicon, copied as-is into the build.

## Before launch

- Replace the placeholder Beavo head and typed "beavo" wordmark with the official `Logos/lockup-horizontal.svg` and `Logos/mark.svg`.
- Fill in: App Store link, contact email, pricing details, Android status, Privacy/Terms/Contact links, English page link.
- The floating cards in the hero ("5 dias seguidos", "Adesivo novo!") are illustrative, not real data.
