# FlowOS — The Adaptive Marketing OS

Replace your entire marketing stack with one system that thinks. Funnels end. Flows don't.

**Live at:** [getflowos.com](https://getflowos.com)

## Project Structure

```
GetFlowOS/
├── index.html          # Main homepage (production entry)
├── flowos-homepage.html # Source/backup of homepage
├── privacy.html        # Privacy policy (placeholder)
├── terms.html          # Terms of service (placeholder)
├── favicon.svg         # Site favicon
├── og-image.png        # Social sharing image (1200×630)
├── vercel.json         # Vercel deployment config
├── ACTION_ITEMS.md     # Your to-do list from the audit
├── .gitignore
└── README.md
```

## Development

Open `index.html` in a browser or run a local server:

```bash
# Using Python
python -m http.server 8000

# Using npx
npx serve .
```

## Deployment

### Vercel

1. Push to GitHub
2. Import the repo in [Vercel](https://vercel.com)
3. Deploy (no build step needed — static HTML)

### Manual

Upload the project folder to any static hosting (Netlify, GitHub Pages, etc.).

## Files

| File | Purpose |
|------|---------|
| `index.html` | Main homepage |
| `privacy.html` | Privacy policy (placeholder — replace before launch) |
| `terms.html` | Terms of service (placeholder — replace before launch) |

## TODO

- [ ] Add `og-image.png` (1200×630) for social sharing
- [ ] Replace placeholder content in `privacy.html` and `terms.html`
- [ ] Replace logo placeholders with real customer logos (or remove section)
- [ ] Add waitlist/signup form or connect CTA buttons to your backend
- [ ] Update `og:url` and `canonical` in index.html when you have a domain
