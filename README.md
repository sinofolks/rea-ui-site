# rea/ui showcase

[Open the website](https://sinofolks.github.io/rea-ui-site/).

This repository contains a prebuilt static website archive (`site.zip`) and its GitHub Pages deployment workflow. Application source and Git history are maintained in a separate private repository. The website intentionally includes copyable component TSX/CSS through its Source panel.

To update, build the website with `/rea-ui-site/` as its base path, replace `site.zip` (with `index.html`, `preview.html`, `assets/`, `.nojekyll`, and provenance notices at the archive root), then commit and push. The Pages workflow extracts and deploys this archive; no private repository access or deployment credential is stored here.

Provenance and the applicable MIT notice are included in the archive as `NOTICE.md` and `licenses/upstream-MIT.txt`.
