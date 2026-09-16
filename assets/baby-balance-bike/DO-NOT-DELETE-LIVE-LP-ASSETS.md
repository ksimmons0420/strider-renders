# ⛔ DO NOT DELETE — LIVE PRODUCTION LANDING-PAGE ASSETS

The images in this folder are **load-bearing**. They are served directly on the
**LIVE** Strider *Baby Balance Bike* landing page:

    https://striderbikes.com/baby-balance-bike-lp/     (BigCommerce Raw Page, id 117)

The page hard-codes them as absolute URLs:

    https://ksimmons0420.github.io/strider-renders/assets/baby-balance-bike/<file>

**Deleting, renaming, or moving this folder takes the live landing page's images
offline — every image 404s on a page that has paid ads pointed at it.**

> This already happened once. On **2026-09-15** a repo-cleanup commit
> ("Move unlaunched ad creative out of this public repo" / "Strip everything but
> the images") removed this folder from `main` and broke the live page **while
> Meta ads were spending against it.** It took an emergency restore + push to fix.

## Files in active use by the live LP — DO NOT REMOVE
- `lifestyle-hero.jpg`
- `lifestyle-gift-boxes.jpg`
- `lifestyle-grandparent.jpg`
- `stage-tummy-time.jpg`
- `stage-sitting-up.jpg`
- `stage-seated.jpg`
- `stage-assisted-walking.jpg`
- `studio-blue-cutout.png`
- `studio-green-cutout.png`
- `studio-pink-cutout.png`

(The other `lifestyle-*` files here are spares from the same shoot — safe to keep.)

## Why they're in this public repo
These are **LAUNCHED** assets, not unlaunched creative — they belong here until the
planned migration to the **BigCommerce CDN (on-domain, via WebDAV)** is done. That
migration is pending WebDAV credentials. **Until it lands, leave this folder intact.**

Owner: Chamber Media (Kyle). Last verified live: 2026-09-16.
