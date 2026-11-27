# Aditya Thapa — Personal Portfolio

This repository contains the static portfolio website and its local image assets. No build tools or package installation are required.

## Project structure

```text
.
├── index.html
├── assets/
│   ├── favicon.svg
│   ├── hero-mask.webp
│   └── hero-portrait.webp
├── .nojekyll
└── README.md
```

## Run locally

Open `index.html` in a browser. For best results, use a local static server.

## Publish with GitHub Pages

1. Create or open your GitHub repository.
2. Upload **all** files and folders in this package to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch `main` and folder `/ (root)`, then save.
6. Wait for GitHub Pages to publish the site.

Keep the `assets` folder beside `index.html`; the page references images using relative paths.
