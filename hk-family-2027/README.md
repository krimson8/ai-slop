# 香港家庭遊 2027

Static itinerary page for the family trip to Hong Kong (13–17 Feb 2027).

Live: https://hk-family-2027.vercel.app

- `index.html` — the whole site: inline CSS + vanilla JS, no build step.
- `images/` — photos from Wikimedia Commons, cropped to 1200×675 JPEG (credits are listed at the bottom of the page).

Hosted on Vercel (project `hk-family-2027`, root directory `hk-family-2027`). The `main` branch is the production branch: pushing to `main` deploys the site.

To edit the itinerary, change the `DAYS` data near the top of the `<script>` in `index.html`. To change a photo, replace `images/<slug>.jpg` and update its entry in `PHOTOS` (author, licence and Commons file path for the credits).
