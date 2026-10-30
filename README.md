# liftin-press

The press kit for [Liftin'](https://liftinapp.co) lives on the website at https://liftinapp.co/press/ (repo nstrm/liftin-website, `src/pages/press.astro`).

This GitHub Pages site at press.liftin.app only keeps the old addresses alive: every page redirects to the website's press kit (`/iphone-duo/` and `/duo/` to its iPhone Duo section), and the files already linked from elsewhere stay where they were:

- `liftin-icon.png` — the 1024 px glass app icon, referenced by artwork tooling.
- `iphone-duo/*.png`, `iphone-duo/liftin-duo-press.zip` — the Duo renders sent with the App Store feature nomination (liftin-app#971).

Static files only; no build step. `CNAME` holds the custom domain.
