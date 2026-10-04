# أطياب الحجاز – Menu

A single-page, right-to-left Arabic menu. Everything lives in `index.html`.

## Host it free on GitHub Pages
1. Create a new repository on GitHub (e.g. `atyab-menu`), set to Public.
2. Upload `index.html` and `README.md` (Add file → Upload files → Commit).
3. Go to Settings → Pages.
4. Under "Build and deployment", choose Source: "Deploy from a branch", Branch: `main`, folder `/ (root)`, then Save.
5. After a minute or two the site is live at `https://YOUR-USERNAME.github.io/atyab-menu/`.

## Editing the menu
Open `index.html` and find the block that starts with `const D=` near the bottom.
Each section is two lines: the section title, then its items written as `name|price|calories` separated by `;`.
