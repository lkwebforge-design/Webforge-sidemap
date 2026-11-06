# WebForge Signature

A responsive static landing page for WebForge Signature.

## Deploy

This repository includes a GitHub Actions workflow at `.github/workflows/deploy.yml` that publishes the site to GitHub Pages whenever changes are pushed to `main`.

If this is the first deployment, open **Settings → Pages** and set **Build and deployment → Source** to **GitHub Actions**. The workflow will then publish the site.

The site is plain HTML, CSS and JavaScript, so it does not require a build step or a Lovable runtime. The published GitHub Pages version does not include the Lovable editor badge.
