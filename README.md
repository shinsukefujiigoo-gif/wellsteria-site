# Wellsteria LLC — Website

Deploy to GitHub Pages:

1. Create a **public** repo (e.g. `wellsteria-site`) and push these files (`index.html`, `CNAME`, `README.md`) to the `main` branch.
2. In the repo, go to **Settings → Pages**, set **Source: Deploy from a branch**, branch **main**, folder **/(root)**, and save.
3. Under **Settings → Pages → Custom domain**, confirm `wellsteria.com` (the `CNAME` file sets this) and enable **Enforce HTTPS**.
4. At your DNS provider add **four A records** for the apex `@` → `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`, and a **CNAME** for `www` → `<username>.github.io`.
5. Wait for DNS to propagate (minutes to ~24h), then verify the site loads at https://wellsteria.com.
