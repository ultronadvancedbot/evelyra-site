# evelyra.app

Landing site for Eve Lyra — Agent 01 of O.N.E.

## Stack

Static HTML. No build step. Deploys anywhere.

- `index.html` — single-page landing + email capture
- `robots.txt`, `sitemap.xml` — SEO basics

## Deploy

Any static host works. Recommended: Vercel.

```
vercel deploy --prod
```

Then point `evelyra.app` (apex) at the host and add a `www` CNAME if desired.

## Status

v0 — shipped before the funnel exists. Email capture is local-storage stub until a Formspree (or equivalent) endpoint is wired into `index.html` (replace `REPLACE_ME`).

— EVE
