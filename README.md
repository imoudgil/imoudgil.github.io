# Portfolio — Ishan Moudgil

Simple static portfolio site. No build step required.

## Preview locally

Open `index.html` in a browser, or run a local server:

```bash
cd portfolio
python3 -m http.server 8080
# visit http://localhost:8080
```

## Deploy to GitHub Pages (free)

### Option A — Personal site (recommended)

1. Create a new GitHub repo named **`imoudgil.github.io`**
2. Push the contents of this `portfolio/` folder to the `main` branch
3. In repo Settings → Pages → Source: **Deploy from branch → main → / (root)**
4. Your site will be live at **https://imoudgil.github.io**

```bash
cd portfolio
git init
git add .
git commit -m "Add portfolio site"
git branch -M main
git remote add origin https://github.com/imoudgil/imoudgil.github.io.git
git push -u origin main
```

### Option B — Project site

1. Create repo `portfolio` (or any name)
2. Push this folder
3. Enable GitHub Pages on `main`
4. Site URL: `https://imoudgil.github.io/portfolio/`

## Customize

- Edit project links in `index.html` when repos go public
- Add a PDF resume link once you host one
- Replace placeholder project cards with GitHub links as you push more repos

## Files

- `index.html` — content and structure
- `styles.css` — layout and theme
- `script.js` — mobile navigation toggle
