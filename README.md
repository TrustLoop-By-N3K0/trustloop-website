# trustloop-website

Marketing site, blog, changelog, and landing pages for TrustLoop.

## What this is

This repo is the public-facing marketing site. It explains what TrustLoop does, shows pricing and examples, and drives signups. It is intentionally separate from the TrustLoop app so it can be deployed, updated, and A/B tested independently.

## Features

- Home, features, pricing, about, FAQ, and contact pages
- SEO-optimized marketing content
- Blog and changelog sections
- Signup CTAs that link to the main TrustLoop app

## Tech stack

- Next.js App Router
- Tailwind CSS v4
- TypeScript
- Netlify

## Getting started

```bash
cp env.example .env.local
npm install
npm run dev
```

Open `http://localhost:3000`.

## Environment variables

| Variable | Description |
| --- | --- |
| `NEXT_PUBLIC_APP_URL` | URL of the main TrustLoop app, e.g. `https://app.trustloop.app` |
| `NEXT_PUBLIC_BLOG_ENABLED` | Toggle the blog section |

## Scripts

| Script | Purpose |
| --- | --- |
| `npm run dev` | Start dev server |
| `npm run build` | Production build |
| `npm run lint` | Run ESLint |

## Deployment

Deploy on Netlify with `npm run build` as the build command and `.next` as the publish directory.

## License

MIT
