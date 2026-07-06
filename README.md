[README.md](https://github.com/user-attachments/files/29682948/README.md)
# Reliability & Controls Insight

Static site — no build step required. Files:

- `index.html` — homepage (hero, coverage pillars, latest articles, about)
- `style.css` — shared design system for the whole site
- `script.js` — shared small script (footer year)
- `articles/` — individual article pages:
  - `preventive-maintenance-fails.html`
  - `scada-integration-101.html`
  - `cost-of-unplanned-downtime.html`

## Publish with GitHub Pages (new repository: `plant-maintenance-control-hub`)

1. Create the repository on GitHub:
   - github.com → **"+"** (top right) → **New repository**
   - Name: `plant-maintenance-control-hub`
   - Visibility: **Public**
   - Create repository (don't add a README from GitHub's template — you already have one here).

2. Upload files, **keeping the folder structure**:
   - `index.html`, `style.css`, `script.js`, and `README.md` go in the **root**.
   - The three files inside `articles/` need to end up inside an **`articles` folder** in the repo.
     When uploading, either drag the whole `articles` folder if your browser supports it, or upload
     each file and rename it to `articles/filename.html` (typing the folder name before the filename
     creates the folder automatically, same trick used for the `assets` folder on the portfolio site).

3. In the repo: **Settings → Pages**.
4. Under **Build and deployment → Source**, choose **Deploy from a branch**.
5. Branch: `main`, folder: **`/ (root)`**. Save.
6. Wait 1–2 minutes. Your site will be live at:
   `https://juandiazave01.github.io/plant-maintenance-control-hub/`

## Adding a new article later

1. Copy one of the existing files in `articles/` as a starting template.
2. Update the `<title>`, the tag, the headline, byline, and body content.
3. Add a new `<article class="article-card">` block to the "Latest" section in `index.html` linking
   to the new file.
4. Upload both the new article file and the updated `index.html`.

## Local preview

Open `index.html` directly in a browser — no server needed.


