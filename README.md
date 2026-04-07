# Khayal Website

Landing page for [Khayal](https://github.com/rawnaqs/khayal) — a local-first, privacy-focused second brain.

**khayal.rawnaqs.io**

## Tech Stack

- [Astro](https://astro.build) — Static site generator
- IBM Plex Mono + Bricolage Grotesque — Typography
- Zero frameworks — Pure HTML/CSS, no JS dependencies

## Structure

```
src/
├── components/     # Page sections (Header, Hero, Features, etc.)
├── layouts/        # Base HTML layout with fonts and meta
├── pages/          # Routes (index.astro = homepage)
└── styles/         # Global CSS variables and resets
public/
├── icon.svg        # Brand icon (also used as favicon)
└── CNAME           # Custom domain for GitHub Pages
```

## Commands

| Command | Action |
|---|---|
| `npm run dev` | Start dev server at `localhost:4321` |
| `npm run build` | Build to `./dist/` |
| `npm run preview` | Preview production build locally |

## Deployment

Deploys to GitHub Pages on every push to `main` via `.github/workflows/deploy.yml`.

Custom domain: `khayal.rawnaqs.io` (configured via `public/CNAME`)

## License

AGPLv3 — [Rawnaqs](https://github.com/rawnaqs)
