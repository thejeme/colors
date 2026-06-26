# Colors

Colors is a tiny static web experiment at [colors.jeme.app](https://colors.jeme.app/).

The page changes its background color once every minute, starting at `#000000` and moving through the full 24-bit hex color range until `#FFFFFF`. There are 16,777,216 colors total, so the full cycle takes about 32 years.

## Local Development

Open [index.html](index.html) directly in a browser, or serve the directory with any static file server.

Example:

```sh
python -m http.server 8080
```

Then visit `http://localhost:8080/`.

## Deployment

This is a static site. Deploy the repository contents to any static host and point the domain to:

```text
https://colors.jeme.app/
```

The production URL is used in the canonical, Open Graph, and Twitter metadata in [index.html](index.html).

## Author

Made by [Eemeli Mark](https://eemelimark.com/).
