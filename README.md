# Galileo Research

Investment research and analysis reports.

## Structure

- `index.html` — Landing page listing all research reports
- `reports/index.json` — Metadata for all reports
- `reports/*.html` — Individual research report pages
- `styles.css` — Clean, minimal styling

## Adding New Reports

1. Add the HTML file to `reports/`
2. Add metadata entry to `reports/index.json`
3. Push to GitHub → auto-deploys via Cloudflare Pages

## Local Development

```bash
python3 -m http.server 8000
# Visit http://localhost:8000
```

## Deployment

Auto-deploys from `main` branch via Cloudflare Pages to `galileo-research.pages.dev`