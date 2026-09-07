# Harby Cheque Command Center v4.0

## Automatic GitHub Pages deployment

This repository is ready for automatic deployment.

### GitHub Pages
1. Upload/push the repository contents to GitHub.
2. Go to **Settings → Pages**.
3. Set **Source** to **GitHub Actions**.
4. Push to `main`.

Every push to `main` triggers `.github/workflows/deploy-pages.yml` and publishes the site.

### Vercel
Import the same repository into Vercel as a static site. No build command is required.

> Note: The current app is offline-first. Enterprise multi-user features still require a deployed backend/API.
