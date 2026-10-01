# Hydro Nexus Analytics — GitHub Pages site

Live site: `https://<your-username>.github.io/<repo-name>/`

## Publish (5 minutes)
1. Create a new **public** repository on GitHub (e.g. `HNA`).
2. **Add file → Upload files** → drag in the *contents* of this folder (index.html, standalone.html, .nojekyll, data/, img/, vendor/). Keep the folders. Commit.
3. **Settings → Pages → Build and deployment → Source: Deploy from a branch → Branch: main / (root) → Save.**
4. Wait 1–2 minutes, then open `https://<your-username>.github.io/<repo-name>/`.

Notes
- Clicking `index.html` inside the GitHub file list only shows code (GitHub never runs HTML there). Always use the github.io address.
- `standalone.html` (11 MB, everything inside one file) also works at `.../<repo-name>/standalone.html`, but GitHub's file browser can't preview a file that large, so it may look empty there.
- `.nojekyll` stops GitHub's Jekyll step from touching the files. If your upload hid it (files starting with "." are hidden on some computers), create it on GitHub: Add file → Create new file → name `.nojekyll` → commit.
