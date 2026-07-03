# Satori — satori-destinations.com

Static one-page site for **Satori**, story-led consulting for boutique hospitality.

- Single file: `index.html` (embedded CSS + minimal JS, no build step).
- Deploys to Netlify from the repo root (see `netlify.toml`).

## Local preview

```bash
python3 -m http.server 8000
# then open http://localhost:8000
```

## Assets

- `logo.png` — the Satori script logo, ideally a tight-cropped **transparent PNG**.
  Until it exists, the header and hero fall back to a styled text wordmark.
