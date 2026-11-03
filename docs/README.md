# ZDOS portfolio static site

This `docs/` directory is the GitHub Pages artifact. Configure repository Pages with **Deploy from a branch**, branch `main`, folder `/docs`. No Actions workflow or workflow permission is required.

For a local preview from the repository root:

```sh
python3 -m http.server 3000 --bind 127.0.0.1 --directory docs
```

The single page uses relative CSS, JavaScript, favicon and artwork paths, so it works at the root of `high-cde.github.io` and under a GitHub Pages project subpath. Manus Preview also uses generated project storage artwork; the checked-in `assets/hero-network.svg` remains a local fallback. The editorial copy and source URLs are documented in `../SOURCES.md`.

The cryptocurrency section describes the experimental local-devnet source and makes no claims about a live token, price, ticker, supply, listing, profit or investment outcome.
