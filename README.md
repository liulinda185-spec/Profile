# Linda Liu — Personal Portfolio Website

A bilingual personal portfolio for **Liu Yingge (Linda)** — Energy Engineer · Climate Researcher · Storyteller.

- `index.html` — English version (entry page)
- `zh.html` — 中文版（中文简历作品集）

Built as a static site: open `index.html` locally, or host on GitHub Pages.

## Publish to GitHub Pages

1. Create a new repository on GitHub (e.g. `linda-portfolio`).
2. From this folder, run:

```bash
git init
git add .
git commit -m "Initial portfolio site"
git branch -M main
git remote add origin https://github.com/<your-username>/linda-portfolio.git
git push -u origin main
```

3. In the repo: **Settings → Pages → Source → Deploy from a branch → `main` / root → Save**.
4. Your site is live at `https://<your-username>.github.io/linda-portfolio/`.

## Notes

- Google Fonts and Font Awesome load from CDNs — an internet connection is required for full styling.
- All images / PDFs are referenced by relative paths, so the whole folder must be uploaded together.
- Six gallery photos referenced by the "Sustain" project modal did not exist anywhere in the source folder; those dead entries were removed from the published copy. If you find the originals, drop them here and update `index.html` / `zh.html`.
