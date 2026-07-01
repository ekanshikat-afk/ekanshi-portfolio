# Ekanshi Katiyar — Portfolio

Two-page portfolio site built with plain HTML + CSS + a bit of vanilla JS. No build step.

- `index.html` — animated splash / intro (particle network + terminal window + code snippet). Same style as the reference site.
- `home.html` — full resume portfolio (About, Skills, Experience, Projects, Education, Contact). Linked from the intro's **Explore Portfolio** button.
- `styles.css` — styles for `home.html`.

## Preview locally

Just open `index.html` in a browser. Or run a tiny local server:

```bash
# from this folder
python -m http.server 8080
# then open http://localhost:8080
```

## Deploy to GitHub Pages

1. Push this folder to a public GitHub repo.
2. In the repo on GitHub: **Settings → Pages → Build and deployment → Source: Deploy from a branch → Branch: `main` / `(root)` → Save**.
3. Wait ~30–60 seconds. Your site is live at `https://<username>.github.io/<repo-name>/`.

## Editing content

All text lives in `index.html` and `home.html`. Colors, spacing, and typography live in CSS variables at the top of `styles.css` (`:root { ... }`) — tweak `--accent`, `--bg`, etc. to re-theme in seconds.

## Add to your resume

Once deployed, add the URL to the header of your resume next to your LinkedIn and email.