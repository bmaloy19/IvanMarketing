# IvanMarketing

Marketing site for **LB Growth**, a small-business marketing consultancy (client project). Single static page, `index.html` + `styles.css`, no JS framework, no build. Deployed by GitHub Pages from `main`; custom domain in `CNAME`.

## Run
- `python3 -m http.server 8000`, then open http://localhost:8000 (or VS Code Live Server).

## Layout
- `index.html`: nav plus about 14 `<section>`s (hero, services, about, contact, …), with SEO `<meta>` tags in `<head>`. Google Fonts: Inter + Playfair Display.
- `LB Growth - New Logo/1–8.png`: the client's logo set (the folder name has spaces; quote paths). Loose `IMG_*.jpeg/png` at the root are photos used by the page.

## Conventions
- Client copy: change wording only when asked, and keep the SEO meta description/keywords in sync with the page.
- The `CNAME` history shows the custom domain was toggled a few times. Don't touch `CNAME` unless asked; pushing `main` deploys.
- `.idea/` and `.vscode/` are editor leftovers; ignore them.
