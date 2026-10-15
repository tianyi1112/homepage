# Tianyi Shi — Personal Homepage

A lightweight, responsive academic homepage hosted on GitHub Pages.

## Files

- `index.html`: profile, introduction, research interests, and publications, in that order.
- `styles.css`: desktop and mobile layout.
- `portrait.jpg`: the supplied profile photograph, preserved at its original aspect ratio.
- `favicon.svg`: site icon.
- `.nojekyll`: serves the static files directly without a Jekyll build.

All links to site assets are relative, so the site works at `/homepage/` and at a custom domain. No third-party fonts, scripts, package installation, or build step are required.

## Adding content

Replace the clearly marked placeholder paragraphs in `index.html`. A publication can be added using:

```html
<article class="publication">
  <h3>Publication title</h3>
  <p>Authors, including <strong>Tianyi Shi</strong></p>
  <p class="venue">Venue, year</p>
  <div class="publication-links">
    <a href="PAPER_URL">Paper</a>
    <a href="CODE_URL">Code</a>
  </div>
</article>
```

Remove the `empty-publications` element when adding real entries.

## GitHub Pages

Repository Settings → Pages → Deploy from a branch → `main` → `/ (root)`.

Website: https://tianyi1112.github.io/homepage/
