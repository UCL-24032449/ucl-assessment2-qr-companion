# UCL Assessment 2 QR Companion

Static one-page companion website for the Team Central 1-16 UCL Assessment 2 poster.

## Site files

- `index.html` is the deployable homepage.
- `assets/pilot-focus-map.png` is the homepage map image used by the page.

## Cloudflare Pages setup

Use these settings when connecting this repository to Cloudflare Pages:

- Framework preset: `None`
- Build command: leave blank
- Build output directory: `/`

After the repository is connected, future updates should be:

```bash
git add index.html assets README.md .gitignore
git commit -m "Update companion site"
git push
```
