# NotaryJotter website

Marketing site for [notaryjotter.com](https://notaryjotter.com), built with Hugo.

## Local development

```sh
hugo server
```

Then open `http://localhost:1313`.

## Production build

```sh
hugo --gc --minify
```

The generated site is written to `public/`.

## Before launch

Replace the placeholder App Store links (`href="#"`) in `layouts/index.html` with the live NotaryJotter App Store URL.
