# Muhammed Mansur Kavak Portfolio

Lean Next.js portfolio focused on simple content management, static export, and deployment-friendly structure.

## Stack

- Next.js 14
- React 18
- Tailwind CSS
- TypeScript

## Scripts

```bash
npm install
npm run dev
npm run lint
npm run typecheck
npm run build
```

## Deployment

The project uses `output: "export"`, so `npm run build` generates a static site in `out/`.

You can deploy the result to:

- Vercel
- Netlify
- GitHub Pages
- Cloudflare Pages
- Any static hosting provider

## CI

GitHub Actions workflow lives at `.github/workflows/ci.yml` and runs:

1. `npm ci`
2. `npm run lint`
3. `npm run typecheck`
4. `npm run build`

## Structure

```txt
src/
  components/
  data/
  lib/
  pages/
  styles/
public/
  media/
```
