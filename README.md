# Pimentel Électrique website

Static site (index.html + styles.css), mobile-first with a desktop layout at 900px+.

Every push to `main` deploys to Cloudflare Pages (project `pimentel-preview`) through
`.github/workflows/deploy.yml`. Repo secrets needed: `CLOUDFLARE_API_TOKEN`, `CLOUDFLARE_ACCOUNT_ID`.

To preview locally, open `index.html` in a browser.
