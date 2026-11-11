# NIL Social Media Benchmark

Static GitHub Pages deployment for the NIL athlete social media benchmarking dashboard.

The published dashboard includes its underlying public-post observations in the static site bundle. Treat the site and repository as shareable with anyone who can access them.

## Deploy

This repository uses GitHub Actions to publish the `site/` folder to GitHub Pages when changes are pushed to `main`.

In the repository settings, set **Pages → Build and deployment → Source** to **GitHub Actions**.

To update the published dashboard, replace the contents of `site/` with the latest reviewed static export, then commit and push to `main`.
