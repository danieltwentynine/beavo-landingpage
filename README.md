# Beavo — landing page

Static landing page for Beavo ("Escova comigo?"), in pt-BR. Plain HTML + CSS, no build step.

## Run locally

```bash
npm run dev
```

Then open the URL it prints (http://localhost:3000 by default). Any static server works; there is no build step.

## Files

- `index.html` — page markup (pt-BR).
- `styles.css` — styles; colours, type, radii and shadows come from the Beavo design system tokens (see `:root`).
- `favicon.svg` — placeholder favicon.
- `package.json` — only a `dev` script that serves the folder locally.

## Before launch

- Replace the placeholder Beavo head and typed "beavo" wordmark with the official `Logos/lockup-horizontal.svg` and `Logos/mark.svg`.
- Fill in: App Store link, contact email, pricing details, Android status, Privacy/Terms/Contact links, English page link.
- The floating cards in the hero ("5 dias seguidos", "Adesivo novo!") are illustrative, not real data.
