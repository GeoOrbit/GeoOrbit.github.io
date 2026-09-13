# GeoAIOrbit Lab — simple HTML website

This is a plain static website. It has no framework, package manager, database,
or JavaScript dependency.

## Files

- `index.html` — GeoAIOrbit Lab home page and compact research-interest buttons
- `research.html` — descriptions of the seven research themes
- `publications.html` — publications grouped by year
- `abouttheresearcher.html` — information about the researcher
- `styles.css` — colors, typography, spacing, buttons, and mobile layout
- `assets/geoorbit-logo.png` — cleaned GeoAIOrbit Lab logo
- `assets/AA3(1).png` — source portrait on the researcher page
- `favicon.svg` — browser icon
- `.nojekyll` — tells GitHub Pages to serve the files directly

## Preview on your computer

Unzip the package and double-click `index.html`. The site works directly from the
folder; no installation or terminal command is required.

## Publish with GitHub Pages

1. Create a public GitHub repository named `GeoOrbit.github.io`.
2. Upload everything inside the `geoorbit-site` folder to the repository root.
3. Open **Settings → Pages** in GitHub.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Choose the `main` branch and `/ (root)`, then save.

The website will be available at `https://geoorbit.github.io/`.

## Edit the website

Open any `.html` file in a text editor. Normal page text appears between HTML tags:

```html
<p>Change this text.</p>
```

The seven home-page research buttons are in the `interest-buttons` block in
`index.html`. Their detailed text is in the matching `<section>` blocks in
`research.html`. Keep each button link and section `id` the same so the links
continue to jump to the correct topic.

To add a publication, copy an existing `<li>...</li>` block in
`publications.html`, paste it under the correct year, and replace the authors,
year, title, journal details, and DOI.

To replace the logo or portrait, keep the filenames in the `assets` folder the
same, including the portrait filename `AA3(1).png`. To change colors or spacing,
edit the variables at the top of `styles.css`.

The navigation bar and footer are repeated in each HTML file. If you add a page
or change a navigation label, make the same small edit in all four files.
