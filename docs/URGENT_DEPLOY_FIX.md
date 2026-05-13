# Deployment Fix

The live site looked unstyled because the page was not reliably loading the CSS.

This package fixes that by:

1. Inlining the CSS into every HTML page in `docs/`.
2. Also placing the same HTML pages at the repo root as a fallback.
3. Adding `.nojekyll` so GitHub Pages serves files plainly.

## What to do

Upload/extract the full contents of this folder into the repository and overwrite existing files.

Then set GitHub Pages to either:

- `main` branch + `/docs` folder, recommended; or
- `main` branch + root folder, also works because fallback HTML pages are included.

After upload, wait 1-3 minutes and hard refresh the website with Ctrl + F5.
