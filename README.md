# The Hills Condominium Association website

Static rebuild of https://thehillsstjohncoa.com (formerly WordPress), hosted on Netlify and deployed from this repository.

- `index.html` – the single page
- `styles.css` – styles
- `assets/` – photo, logo, site icon, and `docs/` with the association PDFs
- `netlify.toml` – publish settings and redirects from the old WordPress file URLs

No build step. Any push to `main` redeploys the site.

To update a document, replace the PDF in `assets/docs/` (keep the same file name, or update the link in `index.html`) and push.
