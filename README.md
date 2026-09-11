# fitsmrt.github.io

Static build of the Fitsmrt landing page, served by GitHub Pages at
<https://fitsmrt.github.io>.

This repository contains **generated output only** — do not edit these files by
hand. The source lives in the private [`fitsmrt/website`](https://github.com/fitsmrt/website)
repository.

## Updating the site

```bash
git clone https://github.com/fitsmrt/website
cd website
npm install
npm run build        # next.config.mjs sets output: 'export' -> ./out
```

Then copy the contents of `out/` over this repository (keeping `.nojekyll` and
this README), commit, and push to `main`.
