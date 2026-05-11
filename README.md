# cxverse pfp

internal tool — drop a photo inside the cxverse frame and export a 1000×1000 png for linkedin.

## use

open the deployed url, double-tap the canvas to choose an image, drag to reposition, scroll or use the slider to zoom, then download.

## run locally

```sh
git clone git@github.com:supajoy/cxversepfp.git
cd cxversepfp
open index.html
```

no build step — it's a single static html file.

## deploy

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/supajoy/cxversepfp)

click the button above to clone the repo into your own vercel account and deploy in one step. requires github access to this repo.

## files

- `index.html` — single-file app (vanilla html/css/js)
- `frame-badge.png` / `frame-dark.png` / `frame-white.png` — overlay variants (1796×1796, drawn at 1000×1000 on export)
