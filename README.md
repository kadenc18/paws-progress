# Paws & Progress v4

Upload **all files** from this folder to the root of your existing GitHub Pages repository, replacing existing files. Under Settings > Pages, publish from `main` / root. Reload the site; if the old version remains, close and reopen the home-screen app or clear the site's cached data (back up first).

## New features
- Barcode scanner using `html5-qrcode` loaded from a CDN; HTTPS and camera permission required. Manual barcode entry works if camera is unavailable. Open Food Facts product lookup needs internet and may have incomplete nutrition information.
- Protein, carbohydrates, fat per entry and daily totals; manual entry and food search support macros.
- Water tracker with editable daily glass goal.
- Daily habit heart rewards and mascot accessory unlocks.
- Weekly habit calendar and streak counter.
- Saved recipes with ingredients, calories, and macros.
- Subtle mascot floating animations and encouraging toast messages.

## Privacy and backup
Data stays in localStorage on this device. Use Settings > Export backup before updating. There is no automatic sync across devices. Existing v1-v3 data uses the same storage key and is retained. Food search, barcode lookup and first-time scanner library loading need internet.
