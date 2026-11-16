# Doforia — Official Website

Official website for Doforia, by Got A dot.

- Software and CI/CD: [gotadot/Doforia](https://github.com/gotadot/Doforia) (currently private).
- Website and GitHub Pages: this repository.
- Release downloads: linked from the website when public releases are available.

## Publish

Open **Settings → Pages** for this repository. Under **Build and deployment**, choose **Deploy from a branch**, branch **main**, folder **/(root)**, and save.

The intended GitHub Pages address is: https://gotadot.github.io/Doforia-Website/

## Site structure

- `index.html`: product landing page and downloads.
- `styles.css`: responsive visual design.
- `script.js`: interactive concept demo.
- `.nojekyll`: keep static site intact.

No build, package installation, API keys, or backend are necessary.

## Releases

This site currently includes an informational link to the software release page. **No binary download has been published yet**, and the software repository is currently private. When a publicly accessible release is published, the website can link directly to a versioned installer or the latest release. Do not use GitHub Pages for secret keys, payment verification, or entitlement logic.
