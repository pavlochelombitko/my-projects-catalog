# pavyel_ — Portfolio

A minimal, dark-themed portfolio site for showcasing projects. Built for GitHub Pages.

## Quick Setup

1. Create a new GitHub repo (e.g. `pavlochelombitko.github.io` or `portfolio`)
2. Upload all 4 files: `index.html`, `admin.html`, `projects.json`, `README.md`
3. Go to **Settings → Pages → Source** and select `main` branch
4. Your site is live!

## Files

| File | Purpose |
|------|---------|
| `index.html` | Main portfolio page — displays projects from `projects.json` |
| `admin.html` | Admin panel — add, edit, delete, reorder projects |
| `projects.json` | Project data file |

## How to Add Projects

1. Open `admin.html` (locally or on your deployed site)
2. Fill in the form: title, description, image URL, link, and tags
3. Click **"Download projects.json"** at the bottom
4. Replace `projects.json` in your GitHub repo with the downloaded file
5. Commit and push — done!

The admin panel stores changes in your browser's localStorage so you can see them instantly on the main page while working locally. For production on GitHub Pages, export and commit the JSON file.

## Images

Use any image URL. Good free sources:
- [Unsplash](https://unsplash.com) — append `?w=600&h=400&fit=crop` to URLs
- Screenshots hosted in your GitHub repo

## Customization

Edit CSS variables at the top of `index.html` to change colors:

```css
--accent: #00e5bf;       /* Main accent color */
--bg-primary: #0a0a0f;   /* Background */
--bg-card: #12121a;       /* Card background */
```
