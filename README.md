# Ziyao Qing – personal website

Plain static HTML/CSS site for GitHub Pages (no build step).

| File | Page |
|---|---|
| `index.html` | Home / About |
| `research.html` | Research experience |
| `publications.html` | Publications |
| `cv.html` | CV |
| `style.css` | Shared styles |
| `images/avatar.svg` | Placeholder avatar – replace with `images/avatar.jpg` and update the `<img src>` in each page |

## Deploy to GitHub Pages

1. On GitHub, create a **public** repository named exactly `<your-username>.github.io`.
2. Upload all files in this folder (Add file → Upload files), or:
   ```
   git init
   git add .
   git commit -m "Initial site"
   git branch -M main
   git remote add origin https://github.com/<your-username>/<your-username>.github.io.git
   git push -u origin main
   ```
3. Repo → Settings → Pages → Source: *Deploy from a branch*, Branch: `main` / `(root)`.
4. After ~1 minute the site is live at `https://<your-username>.github.io/`.
