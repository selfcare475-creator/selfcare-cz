# Self Care Pharmacy — Czech storefront

Static site (selfcare-cz.com). Auto-deploys to Cloudflare Pages on push to `main`.

- Site files: `public/`
- Catalog/categories/prices load live from Supabase at runtime (baked JSON in `public/` is the fallback for first paint).
- Deploy: GitHub Actions → Cloudflare Pages (`.github/workflows/deploy.yml`).

> Test target is currently the `generaltest` Pages project. Switch `--project-name` to `selfcare-cz-backup` for live.
