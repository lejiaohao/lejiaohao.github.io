# Lejiaohao Homepage

Static homepage for the Lejiaohao Project.

This site is designed for GitHub Pages and Cloudflare Pages. It uses plain HTML, CSS, and a small JavaScript file. No build step is required.

## Structure

```text
index.html
pages/
  future-studies/
    index.html
  conceptual-designs/
    index.html
  science-fiction/
    index.html
  interactive/
    index.html
  tools/
    index.html
  about/
    index.html
assets/
  css/site.css
  js/site.js
  images/background_dark_webpage_multi_galaxies.png
```

## Background Image

The current background image is:

```text
assets/images/background_dark_webpage_multi_galaxies.png
```

Replace it with another image using the same path, or update the `--hero-image` variable in `assets/css/site.css`.

## Deployment

For GitHub Pages, place these files in the root of the `lejiaohao.github.io` repository and enable Pages in repository settings.

For Cloudflare Pages, create a static project from this repository. No build command is required.

## Language

The site is English-first for now, with Chinese project labels included where useful. A language switch placeholder is included in the navigation.
