## Denerio — Marketing Site

Public repository for the Denerio homepage, deployed to **https://denerio.com** via GitHub Pages.

### Contents

- `site/` — static HTML/CSS homepage
- `.github/workflows/deploy-pages.yml` — deploy workflow

Platform code (backend, frontend, architecture docs) lives in a **separate private repository**, not here.

### Local preview

```powershell
cd site
python -m http.server 8080
# open http://localhost:8080
```

### Deploy

Push changes under `site/` to `main`. The GitHub Actions workflow publishes to GitHub Pages.

Owner setup (once): **Settings → Pages → Build and deployment → GitHub Actions**
