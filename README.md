# Reward Geni API Docs

Simple static documentation site for Reward Geni Client Exchange API.

## Tech

- HTML
- CSS
- JavaScript

## Run locally

```bash
python -m http.server 8000
```

Open: http://localhost:8000

## Main files

- index.html
- docs/getting-started.html
- docs/api.html
- docs/guides.html
- styles.css
- script.js
- search-index.json

## Deploy

- Push to main branch.
- GitHub Actions workflow deploys to GitHub Pages.

## BASE_URL setup for deployment

Set one of these in GitHub repository settings:

- Actions Variable: RG_BASE_URL (recommended)
- or Actions Secret: RG_BASE_URL

During deploy, workflow updates config.js automatically.
