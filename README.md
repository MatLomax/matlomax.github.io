# matlomax.github.io

My personal site / CV — live at **https://matlomax.github.io/**.

This repository only **hosts** the published site. The content is built from
source in [MatLomax/astro-cvitae](https://github.com/MatLomax/astro-cvitae) and
deployed here automatically by GitHub Actions on every push to that repo's
`main` branch.

- The built static site is force-pushed to the **`gh-pages`** branch, which
  GitHub Pages serves at the root domain.
- **Don't edit the `gh-pages` branch by hand** — it is overwritten on every
  deploy. Make all changes in `astro-cvitae`.
