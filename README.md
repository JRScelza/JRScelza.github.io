# jerome-scelza.github.io

Personal portfolio site for Jerome R. Scelza. It's a static page with no build step.

## Deploy to GitHub Pages

1. On GitHub, create a new **public** repository named `<your-username>.github.io`. With that name the site is served at `https://<your-username>.github.io`.
2. Upload everything in this folder to the repo root: `index.html`, `.nojekyll`, `README.md` and the `assets/` folder. You can drag and drop them via **Add file → Upload files**.
3. Go to **Settings → Pages** and set **Source: Deploy from a branch**, **Branch: `main` / root**, then save.
4. The site goes live within about a minute.

Using a different repo name (for example `portfolio`) works too. The site is then served at `https://<your-username>.github.io/portfolio/`.

### Custom domain (optional)

To use a custom domain such as `jeromescelza.com`, add it under **Settings → Pages → Custom domain**. Then create DNS records at your registrar:
- `A` records for `@` pointing to `185.199.108.153`, `185.199.109.153`, `185.199.110.153` and `185.199.111.153`
- a `CNAME` record for `www` pointing to `<your-username>.github.io`

Once DNS resolves, tick **Enforce HTTPS**.

## Editing

All content and styles live in `index.html`. To update the downloadable résumé or biosketch, replace the PDFs in `assets/` and keep the same file names.
