# Aditya Thapa — Personal Portfolio

A static, GitHub Pages-ready portfolio website. Images and the favicon are stored separately in `assets/`. No build step or package installation is required.

## Repository structure

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

## Deploy with GitHub Pages

1. Create a GitHub repository (for a user site, name it `YOUR-USERNAME.github.io`).
2. Upload **all** files and folders from this package to the repository root. Keep the `assets` folder beside `index.html`; do not upload only the HTML file.
3. Open **Settings → Pages** in the repository.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the `main` branch and `/(root)`, then save.
6. Wait for GitHub Pages to publish the site.

## Run locally

Open `index.html` in a browser. Keep the `assets` folder in the same directory so the images and favicon load correctly.
