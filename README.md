# Vite + Vue 3 + TypeScript + Element Plus + Tailwind CSS

This project is initialized with:

- Vite
- Vue 3
- TypeScript
- Element Plus
- Tailwind CSS (v4 with `@tailwindcss/vite`)

## Development

```bash
npm install
npm run dev
```

## Build

```bash
npm run build
npm run preview
```

## Deploy to GitHub Pages

This repository includes GitHub Actions workflow: `.github/workflows/deploy-pages.yml`.

After enabling **Settings -> Pages -> Build and deployment -> GitHub Actions**, pushes to `main` will:

1. Build the Vite project
2. Upload `dist` as Pages artifact
3. Deploy to GitHub Pages

`vite.config.ts` automatically sets `base` in CI for GitHub Pages path deployment.
