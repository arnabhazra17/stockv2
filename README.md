# Personal website template

Static portfolio site built from your JPG and EPS assets. No build step — deploy as plain HTML to any Git host.

## Structure

```
index.html          Landing page
css/styles.css      Styles
js/main.js          Mobile nav + footer year
assets/images/      Your images and vector logo
```

## Customize

1. Open `index.html` and replace **Your Name**, email, LinkedIn URL, and project copy.
2. Swap images in `assets/images/` if you add new work (keep filenames or update paths in HTML).

## Deploy with Git (GitHub Pages)

```bash
cd "C:\Users\arhazra\OneDrive - Nokia\2personal-website"
git init
git add .
git commit -m "Initial personal site template"
git branch -M main
git remote add origin https://github.com/YOUR_USER/YOUR_REPO.git
git push -u origin main
```

In GitHub: **Settings → Pages → Build and deployment → Source: Deploy from branch → `main` / `/ (root)`**.

Your site will be at `https://YOUR_USER.github.io/YOUR_REPO/`.

## Other hosts

- **Netlify / Vercel**: Connect the repo; publish directory is the repository root.
- **GitLab Pages**: Use a static site job pointing at the root, or push to GitLab and enable Pages.

## Assets

| File | Use |
|------|-----|
| `invenza-dashboard-promo.jpg` | Hero + portfolio |
| `aura-campaign-dashboard.jpg` | Portfolio |
| `aura-logo.eps` | Download link (browsers do not display EPS inline) |
