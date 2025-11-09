
# AOR 5357-23 Unit 102 v1 — PWA (PDF Export Fix)

## What's new
- Fixed **Save Draft** reliability (persistent storage on iPad).
- Fixed **Export to PDF** with a fallback print-based export.
- Added small status pill showing save mode (persistent/session-only).

## Files included
- index.html (ready: save, load, delete photo, multi-criteria, PDF export)
- manifest.webmanifest
- sw.js (cache v5)
- icons/ (180, 192, 512 png)

## Upload steps
1. Create a **public** repo on GitHub (e.g., aor-observation-report).
2. Upload ALL files from this zip to the repo **root**.
3. Go to **Settings → Pages → Source → Deploy from a branch**.
   - Branch: **main**, Folder: **/** (root)
   - Click **Save**.
4. Visit your site at:
   https://YOUR-USERNAME.github.io/aor-observation-report/
5. On iPad Safari → Share → Add to Home Screen.

## Updating
If your iPad doesn’t show the update, open **sw.js**, change CACHE_NAME (e.g., v6), commit, refresh twice.
