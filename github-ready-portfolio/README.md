# Aditya Thapa — Personal Portfolio

A responsive, single-page personal portfolio website built with HTML, CSS, and
vanilla JavaScript.

## Project structure

```text
.
├── index.html
├── assets/
│   └── images/
│       ├── profile.jpg
│       ├── favicon.svg
│       ├── favicon-64.png
│       └── apple-touch-icon.png
├── .nojekyll
└── README.md
```

## Run locally

No build tools or package installation are required.

1. Download or clone this repository.
2. Open `index.html` in a browser.

For a local development server, run:

```bash
python -m http.server 8000
```

Then visit <http://localhost:8000>.

## Publish with GitHub Pages

1. Create a GitHub repository and upload the contents of this folder.
2. Open **Settings → Pages** in the repository.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select the `main` branch and the `/ (root)` folder, then save.
5. Wait for GitHub Pages to publish the site. The published URL will appear in
   the Pages settings.

The homepage is named `index.html`, and all local image references use
repository-relative paths, so the site works from a GitHub Pages project URL.

## Customization

- Edit the text and links directly in `index.html`.
- Replace `assets/images/profile.jpg` to update the profile photo. Keep the
  same filename, or update the image path in the HTML.
- Replace the favicon files in `assets/images/` to update the browser and
  mobile icons.
- The site uses Google Fonts (DM Sans). If Google Fonts is unavailable, it
  falls back to system sans-serif fonts.

## Notes

- No framework, build step, or external JavaScript library is required.
- The page's CSS and JavaScript remain inside `index.html`.
- The profile image and favicon assets are stored as separate files rather
  than large embedded Base64 strings, making the repository easier to maintain.
