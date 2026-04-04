# Setup

This README only covers local setup and run commands.

## Requirements

- Node.js 20+
- npm 10+

## Install

```bash
git clone https://github.com/BlokusPokus/portfolio.git
cd portfolio
npm install
```

## Run locally

```bash
npm run dev
```

The app runs at `http://localhost:1234`.

## Build for production

```bash
npm run build
```

This runs `astro check` and then builds the site into `dist/`.

## Preview production build

```bash
npm run preview
```

## Useful scripts

- `npm run dev` - start dev server
- `npm run start` - alias of `npm run dev`
- `npm run build` - type-check + production build
- `npm run preview` - preview `dist/`
- `npm run astro` - run Astro CLI
- `npm run prettier` - format project files

## Minimal configuration before deploy

- Update `src/consts.ts` (`SITE.href`, title, metadata, nav/social links).
- Update `astro.config.ts` (`site`) to your production domain.
