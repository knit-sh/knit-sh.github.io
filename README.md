# knit-sh.github.io

This repository hosts the published **Knit** website. Its content is generated —
do not edit it by hand.

- **Source.** The site is built from
  [`knit-sh/knit`](https://github.com/knit-sh/knit) by its `make web` target:
  the landing page (`web/`) plus the Sphinx documentation (`docs/`).
- **Publishing.** The `Documentation` workflow in `knit-sh/knit` runs `make web`
  on each push to `main` and pushes the result to the **`gh-pages`** branch of
  this repository. GitHub Pages serves that branch.
- **URL.** The site is served at **https://knit.sh/** (custom domain), with the
  documentation under **https://knit.sh/docs/**. `https://knit-sh.github.io/`
  redirects to `knit.sh`.

## Editing

To change the site, edit the sources in `knit-sh/knit` (the `web/` directory for
the landing page, `docs/` for the documentation) and push to its `main` branch;
the workflow rebuilds and republishes here.

The `gh-pages` branch is overwritten on every publish, so any manual change there
is lost. The `main` branch holds only this README and the license.
