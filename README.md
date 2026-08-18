# SA+GE Portfolio — Free Static Website

This is a lightweight portfolio site designed to echo the minimalist Squarespace aesthetic from the reference screenshot while positioning SA+GE around:

- Scan to BIM
- Scan to 2D CAD
- Scan to Civil 3D
- Point cloud processing

## Files

- `index.html` — all page content and structure
- `styles.css` — visual design and responsive layout
- `assets/` — reserved for your project images

## Replace the sample content

Search `index.html` for:

- `ADD PROJECT IMAGE`
- `Replace with project`
- `your@email.com`
- the About paragraph

The sample technical graphics are CSS-only placeholders. Replace each project-image panel with your actual project screenshots.

## Publish free with GitHub Pages

GitHub Pages can host a static site directly from a GitHub repository on the free plan for public repositories.

1. Create a GitHub account if you do not have one.
2. Create a new **public** repository named `<yourusername>.github.io`.
3. Upload `index.html`, `styles.css`, and the `assets` folder.
4. Go to **Settings → Pages**.
5. Select the `main` branch as the publishing source.
6. Open the published `https://<yourusername>.github.io/` address.

GitHub's official documentation:
https://docs.github.com/en/pages/getting-started-with-github-pages

## Adding your own images

Put images into `assets/`, for example:

`assets/project-01.jpg`

Then replace a project placeholder in `index.html` with an image element such as:

`<img src="assets/project-01.jpg" alt="Scan to BIM project">`

For a portfolio, use real project screenshots rather than the CSS placeholder graphics.
