# Paws & Progress 🐕🐹

A mobile-first, Peru-red-and-white calorie and daily habit tracker. No build tools or paid hosting required.

## Host on GitHub Pages

1. Sign into [github.com](https://github.com) and create a **public** repository named `paws-progress` (or any name).
2. Select **Add file → Upload files** and upload the **contents of this folder** directly to the repository root (`index.html`, `app.js`, `styles.css`, icons, etc.). Commit the files. **Do not upload only the ZIP file.**
3. Go to **Settings → Pages**. Under **Build and deployment**, choose **Deploy from a branch**, select **main** and **/(root)**, then **Save**.
4. After deployment, open `https://YOUR-USERNAME.github.io/paws-progress/` (replace the username and repo name if different). The first deployment may take a few minutes.

## Add it to your iPhone home screen

1. Open the deployed site in **Safari** on your iPhone.
2. Tap the **Share** button and choose **Add to Home Screen** (on some iOS versions this is under Share → More).
3. Keep **Open as Web App** enabled if offered, then tap **Add**.
4. Launch **Paws** from your home screen; it opens in an app-like standalone view.

## Using the app

- **Home** shows today's calorie total, your goal, and your habits.
- **Food → Add Food** searches Open Food Facts online. Pick a result and enter grams; calories are estimated from its per-100g value. Choose **Custom entry** to enter a food and its calories directly. Favorite either type of entry for quick reuse.
- **Tasks** lets you check off habits and create/remove your own.
- **History** lets you select past days and review or edit entries.
- **Settings** lets you adjust your daily calorie goal and **Export backup** / **Import backup**.

## Important notes

- All records are stored in **localStorage on the current device/browser**, not GitHub. They do not sync across devices. Safari and an installed home-screen web app may have separate storage; use **Export backup** and **Import backup** if necessary.
- **Back up regularly**: browser storage can be cleared. Never rely on local storage as your only permanent copy.
- Food search requires internet and depends on Open Food Facts availability and user-contributed nutrition data. Manual entry works offline after the site has loaded/cached once.
- GitHub Pages serves static files; there is no account or cloud database in this version.
- This is a personal tracking tool, not medical or dietary advice.

## Updating

Upload changed files and commit. The site will redeploy automatically. If an installed app appears stale, close and reopen it while connected to the internet. For larger updates, bump the cache name in `sw.js`.

## Version 3 visual update
This version uses illustration crops from the approved original concept mockup to closely match its mascots. Upload **all** files, including the four new PNGs, to the same GitHub Pages directory. Your existing browser data is preserved because the storage key has not changed. Export a backup first.
