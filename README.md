# callMechanic

> Your trusted mechanic — anywhere, any vehicle.

🌐 **Live site:** [https://govardhangithub.github.io/callmechanic/](https://govardhangithub.github.io/callmechanic/)

This repo hosts the public marketing & legal pages for the **callMechanic** mobile app (privacy policy, terms, contact). Built with [MkDocs Material](https://squidfunk.github.io/mkdocs-material/) and auto-deployed to GitHub Pages on every push to `main`.

## Local preview

```bash
pip install -r requirements.txt
mkdocs serve
# → http://127.0.0.1:8000
```

## Build

```bash
mkdocs build --strict
# → ./site/ contains the static HTML
```

## Deploy

Just push to `main` — the GitHub Actions workflow at `.github/workflows/deploy.yml` builds and deploys to GitHub Pages automatically.

## Repo structure

```
docs/
  index.md         landing page (hero + features + vehicles)
  privacy.md       Privacy Policy (referenced by Play Store listing)
  terms.md         Terms & Conditions
  contact.md       contact page
  stylesheets/
    extra.css      brand colors + custom components
mkdocs.yml         site config
requirements.txt   pip deps
.github/workflows/
  deploy.yml       auto-deploy on push to main
```

## Contact

[mopur.govardhan05@icloud.com](mailto:mopur.govardhan05@icloud.com)
