# AdFrame website

The AdFrame Media website (adframe.io). The site lives in `public/`.

- `public/index.html` is the homepage. Booking link, tracking IDs and videos are set near the top of the file.
- `public/privacy.html` is the privacy policy.
- The site is hosted on GitHub Pages. Every push to the `main` branch republishes it automatically (see `.github/workflows/pages.yml`).
- `wrangler.jsonc` is kept in case the site moves to Cloudflare later.
