
# AOR 5357-23 Unit 102 v1 — PWA (Ready to Upload)

## Files
- index.html (patched: iPad signature + robust Save/Load + multi-criteria)
- manifest.webmanifest
- sw.js (cache v4)
- icons/ (180, 192, 512 png)

## Publish to GitHub Pages
1. Create a public repo (e.g., aor-observation-report).
2. Upload ALL files in this zip (index.html, manifest.webmanifest, sw.js, icons/ folder) to the repo root.
3. Settings → Pages → Source: Deploy from a branch. Branch: main, folder: /(root). Save.
4. Open: https://YOUR-USERNAME.github.io/YOUR-REPO-NAME/
5. On iPad Safari: Share → Add to Home Screen.

## Updating
If changes don’t appear, open sw.js and bump CACHE_NAME to a new version (e.g., v5), commit, then refresh twice.
