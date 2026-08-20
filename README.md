# MassComm Solutions — Astro clone

A responsive, single-page Astro implementation inspired by the current MassComm Solutions website.

## Run locally

```bash
npm install
npm run dev
```

Open the local address shown in the terminal (normally `http://localhost:4321`).

## Production build

```bash
npm run build
npm run preview
```

The deployable static output is generated in `dist/`.

## Main files

- `src/pages/index.astro` — page content and interactions
- `src/styles/global.css` — complete responsive styling
- `public/assets/` — locally stored imagery
- `public/fonts/` — locally stored brand fonts

The forms currently show an on-page success message. Connect their submit handlers to your preferred email service, CRM, or Astro API endpoint before launch.
