# rally-website

Marketing website and interactive demo for [Rally](https://rally.echoaisms.com) by Echo AI LLC — an AI-native group-buying product for Shopify merchants and everyday organizers.

This repo contains only the public website and the demo. The Rally product itself lives in a separate repo.

## Pages

- `index.html` — Landing page (`/`)
- `demo.html` — Interactive demo (`/demo`)
- `support.html` — Support (`/support`)
- `mcp-docs.html` — MCP documentation (`/mcp-docs`, linked from Support)
- `privacy.html` — Privacy Policy (`/privacy`)
- `terms.html` — Terms of Service (`/terms`)

## Local preview

Serve the folder:

```bash
python3 -m http.server 8080
```

Then visit `http://localhost:8080`.

## Deploy

Hosted on Vercel (project `rally-website`) at `rally.echoaisms.com`. Vercel serves the `public/` folder, so copy any edited root files into `public/` before deploying:

```bash
npx vercel --prod --yes
```
