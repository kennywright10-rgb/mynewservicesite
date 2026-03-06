# mynewservicesite.com

Lead-gen platform for pitching custom website mockups to local service businesses.

## Structure

```
/                          → Landing page (mynewservicesite.com)
/alpharetta-plumber/       → Alpharetta Plumber mockup demo
```

## Adding a New Prospect

1. Create a new folder: `mkdir prospect-slug`
2. Drop their mockup `index.html` inside
3. Push to GitHub — Vercel auto-deploys
4. Send them: `mynewservicesite.com/prospect-slug`

## Deployment

Hosted on Vercel. Every push to `main` auto-deploys.

- Root domain: `mynewservicesite.com` → `/index.html`
- Prospect pages: `mynewservicesite.com/[slug]` → `/[slug]/index.html`
