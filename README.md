
# AOR 5357-23 Unit 102 v1 — PWA (Dual Signatures + Header Fields)

## What's new
- Top header added: "Applying Health, Safety & Environmental Considerations" with inputs:
  - Candidate name, Date, Job Description, Site address
- Two smaller signature boxes:
  - Assessor name + signature
  - Learner name + signature
- Save/Load now includes all new fields and both signatures.

## Files included
- index.html (this build)
- manifest.webmanifest
- sw.js (cache v6)
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
If you don't see changes, open **sw.js**, bump CACHE_NAME to a new version (e.g., v7), commit, refresh twice.
