# our-little-holliday

This repository was renamed from `-our-little-holliday` to remove a leading hyphen that can cause routing/URL issues (404 errors in some clients).

Repository (current):
- https://github.com/holliday91/our-little-holliday

Pages site (after rename and rebuild):
- https://holliday91.github.io/our-little-holliday/

If you still see a 404 when opening the repository or Pages site, try clearing your browser cache or use an incognito window. GitHub creates redirects from the old repo URL to the new one but caches can show a 404 briefly.

How to rename the repository (web UI):
1. Go to Settings: https://github.com/holliday91/our-little-holliday/settings
2. Under "Repository name" change the name if needed.
3. Click "Rename" and confirm.

How to rename using GitHub CLI:
- gh repo rename holliday91/-our-little-holliday --name our-little-holliday

After renaming locally:
- Update your remote: git remote set-url origin git@github.com:holliday91/our-little-holliday.git
  (or use the HTTPS URL)

What I changed here:
- Updated README with clickable repo and Pages links and rename notes.
- Updated index.html to make the QR clickable and added accessibility improvements.
- Added assets/registry-qr.svg placeholder.
- Added .nojekyll to trigger a Pages rebuild.

If you'd like, I can replace the placeholder SVG with a scannable PNG if you upload one, or make further content edits. Just upload the image or tell me what to change.
