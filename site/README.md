# ZDOS portfolio static site

The GitHub Pages artifact is the `site/` directory. The project also contains an Actions workflow at `.github/workflows/pages.yml` that deploys that directory from the `main` branch after GitHub Pages has been configured to use GitHub Actions.

For a local preview from the repository root:

```sh
python3 -m http.server 3000 --bind 0.0.0.0 --directory site
```

The single page uses relative CSS, JavaScript and favicon paths, so it also works when hosted under a GitHub Pages project subpath. Preview uses the generated hero from Manus project storage; the checked-in `assets/hero-network.svg` remains a local fallback for GitHub Pages. The editorial copy and source URLs are documented in `../SOURCES.md`.

The cryptocurrency section describes the experimental local-devnet source and makes no claims about a live token, price, ticker, supply, listing, profit or investment outcome.
