# AdFrame website

The AdFrame Media website (adframe.io). The site lives in `public/`.

- `public/index.html` is the homepage. Booking link, tracking IDs and videos are set near the top of the file.
- `public/privacy.html` is the privacy policy.
- `wrangler.jsonc` tells Cloudflare to serve the `public/` folder.

Every push to the `main` branch redeploys the site on Cloudflare.
