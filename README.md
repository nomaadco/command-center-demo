# Command Center Demo

A click-through demo of Command Center with made-up data, published at https://demo.nomaad.co (password protected).

- Everything here is sample data. Nothing connects to Google, and nothing you change is saved.
- `site/index.html` is the whole demo. It is rebuilt from the app and replaced by a pull request when the demo is refreshed.
- On every push to `main`, `.github/workflows/deploy.yml` locks the page with the `SITE_PASSWORD` secret (StatiCrypt) and publishes it to GitHub Pages.
