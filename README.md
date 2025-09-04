# Fluid Unit Converter (Black & Gray)

This repository contains a single-file HTML fluid unit converter with a black & gray theme. The file `index.html` is ready to publish via **GitHub Pages**.

## What's included
- `index.html` — the complete converter (open this file directly in a browser or publish with GitHub Pages).
- `README.md` — this file with upload & troubleshooting instructions.

## Quick publish (GitHub web UI — good for iPad)
1. Sign in to GitHub and create a **new repository** (e.g., `fluid-converter`). Set it to **Public**.
2. In the repo page, click **Add file → Upload files** and drag `index.html` and `README.md` into the drop area. (You can also upload the ZIP and unzip locally first.)
3. Commit the upload (scroll down and click **Commit changes**).
4. Go to **Settings → Pages** (or **Settings → Pages / GitHub Pages**) in the repository settings.
5. Under **Source**, choose **Branch: `main`** and **Folder: `/ (root)`**, then click **Save**.
6. Wait ~30–90 seconds. Your site will be available at: `https://<your-username>.github.io/<repo-name>/`

## Publish via command line (desktop)
```bash
git init
git add index.html README.md
git commit -m "Initial commit: add Fluid Unit Converter"
git branch -M main
git remote add origin https://github.com/<your-username>/<repo-name>.git
git push -u origin main
```
Then enable GitHub Pages in **Settings → Pages** (branch: `main`, folder: `/`).

## Common issues and fixes
- **404 after publishing**: Make sure `index.html` is in the root of the repository (not inside a folder). Check Pages settings to confirm `main` branch + `/ (root)` selected.
- **File not found / blank page**: Verify the filename is exactly `index.html` (lowercase) and you committed the file. GitHub Pages is case-sensitive.
- **Still not live**: Wait 30–120 seconds, then refresh. If it still fails, check repository visibility (Pages on public repos works immediately).
- **I see old content / cached**: Do a hard refresh (Ctrl+Shift+R or Shift+Reload). Try in a private window.
- **Clipboard/copy doesn’t work on iPad**: Safari may require a user gesture; use the copy buttons carefully or select the text manually.

## Need help?
If you want, I can:
- Create the GitHub repo and push these files for you (I can't access your GitHub without your credentials, but I can give exact commands and the content ready to paste).
- Add a `LICENSE` file, favicon, or a short `index.html` meta description for SEO.
