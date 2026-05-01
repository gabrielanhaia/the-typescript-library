# The TypeScript Library — landing page (source)

This repo holds the **source** of the public landing page for
**_The TypeScript Library_**, a five-book collection by Gabriel Anhaia.

The page is deployed at:

> [https://xgabriel.com/the-typescript-library/](https://xgabriel.com/the-typescript-library/)

The repo is the editable source. The site is hosted on `xgabriel.com`,
not on GitHub Pages — so changes here have to be uploaded to
xgabriel.com to go live.

## What's here

- `index.html` — single-page landing site.
- `style.css` — dark-themed styles matching the cover aesthetic.
- `covers/` — the 5 *TypeScript Library* covers.
- `covers/other-books/` — the 8 pocket-guide covers shown in the
  "Also by Gabriel Anhaia" section.

## Deploying to xgabriel.com

The site is static — three files plus images, no build step. To deploy:

1. Pull the latest from this repo (`git pull` on your local clone).
2. Upload `index.html`, `style.css`, and the entire `covers/` directory
   to `xgabriel.com/the-typescript-library/` on your hosting.
3. Verify the page loads at
   <https://xgabriel.com/the-typescript-library/>.

Image paths in `index.html` are all relative (`./covers/...`), so they
work as long as the directory layout is preserved on the server. No
absolute URLs to fix at deploy time.

## Companion code

Runnable, CI-verified examples for all five books live in the public
examples repo:

> [github.com/gabrielanhaia/the-typescript-library-examples](https://github.com/gabrielanhaia/the-typescript-library-examples)

## License

The HTML and CSS in this repo are released under the MIT license. The
cover images are © Gabriel Anhaia, all rights reserved.
