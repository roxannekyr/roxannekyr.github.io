

# Roxani Kyritsi portfolio website 

This folder is a ready-to-host static website:

- `index.html` — the whole portfolio, self-contained (styles, fonts and scripts inlined)
- `assets/` — project screenshots and diagrams referenced by the page

No build step, no server code. Any static host works.

## GitHub Pages 
Claude Code prompt:

> "Deploy the contents of this folder to GitHub Pages on my account (roxannekyr). Create a public repo named `portfolio`, push index.html and assets/, and enable Pages from the main branch root."

Manual steps if you prefer:
1. Create a public repo, e.g. `roxannekyr/portfolio` (or `roxannekyr.github.io` for a cleaner URL).
2. Put `index.html` and `assets/` at the repo root and push.
3. Repo Settings → Pages → Source: `main` branch, `/ (root)` → Save.
4. Site goes live at `https://roxannekyr.github.io/portfolio/` (or `https://roxannekyr.github.io/`).
<!--
## Option B — Netlify / Vercel / Cloudflare Pages (also free)

Drag-and-drop this folder in their dashboard, or ask Claude Code to run their CLI (`netlify deploy`, `vercel`, `wrangler pages deploy .`).

## Notes

- Keep `assets/` next to `index.html` — the screenshots are loaded relatively.
- To update the site later, replace `index.html` with a fresh export and push again.

-->
