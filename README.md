
# AOR 5357-23 Unit 102 v1 — PWA Starter

This folder lets you publish your observation report as an **installable app (PWA)** on GitHub Pages.

## Files
- `index.html` — your full working report
- `manifest.webmanifest` — app settings (name, icons, scope)
- `sw.js` — service worker for offline use
- `icons/` — app icons (180, 192, 512 px)

## Publish to GitHub Pages (no command line needed)
1. Go to github.com and create a **new repository** (Public). Name it like `aor-observation-report`.
2. Click **Add file → Upload files** and upload the **contents of this zip** (all files and the icons folder).
3. After upload, make sure `index.html` is at the **root** of the repo (not inside another folder).
4. Go to **Settings → Pages**.
   - Source: **Deploy from a branch**
   - Branch: **main**, folder **/** (root)
   - Click **Save**
5. Wait ~1 minute. Your site will be available at: `https://YOUR-USERNAME.github.io/REPO-NAME/`

## Install on iPad
1. Open that URL in **Safari**.
2. Tap **Share → Add to Home Screen**.
3. Open from your home screen. It runs full-screen and offline.

## Tips
- To update, change files and commit again. If changes don’t appear, bump the cache name in `sw.js` (e.g., `obs-report-cache-v2`).
- If you rename the repo, no changes needed because `start_url` and `scope` in the manifest are set to `"."` (relative).
