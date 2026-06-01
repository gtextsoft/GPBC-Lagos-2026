# GPBC 2026 — Lagos Edition

Static landing page for the Global Property Brokers Conference 2026.

## Local preview

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000).

## Deploy to Vercel

### Option A — Git (recommended)

1. Push this repository to GitHub, GitLab, or Bitbucket.
2. In the [Vercel dashboard](https://vercel.com/new), import the repository.
3. Use the default settings (no framework; root directory `.`).
4. Deploy. Production will serve `index.html` at `/`.

### Option B — Vercel CLI

```bash
npm i -g vercel
vercel login
vercel          # preview
vercel --prod   # production
```

## Files

| File | Purpose |
|------|---------|
| `index.html` | Site entry (served at `/`) |
| `vercel.json` | Static hosting and security headers |

Registration submissions use [Formspree](https://formspree.io); no server-side code is required on Vercel.
