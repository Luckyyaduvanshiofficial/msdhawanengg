# M/S Dhawan Electrikal Engineering Website

Static website for **M/S Dhawan Electrikal Engineering**.

## Project Structure

- `index.html` — Main landing page
- `robots.txt` — Search engine crawler rules
- `sitemap.xml` — Sitemap metadata (updated to 2026)
- `.nojekyll` — Disables Jekyll processing on GitHub Pages
- `assets/` — Images, favicon, and other static assets

## Run Locally

Open `index.html` directly in your browser, or use any static server.

## Deploy on GitHub Pages

1. Push this repository to GitHub.
2. Open your repository on GitHub.
3. Go to **Settings → Pages**.
4. Under **Build and deployment**:
   - **Source**: `Deploy from a branch`
   - **Branch**: `main`
   - **Folder**: `/ (root)`
5. Save and wait for deployment.

Your site will be available at:

- `https://<your-username>.github.io/<repository-name>/`

## Notes

- `.nojekyll` is included so folders/files starting with `_` or static assets are served correctly.
- If you later use a custom domain, update the sitemap URLs accordingly.
