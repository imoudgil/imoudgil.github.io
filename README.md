# My portfolio website

This folder is my personal portfolio site — the page recruiters visit to see my projects and contact info.

**Live site (after you publish):** https://imoudgil.github.io

## What's in here

| File | What it does |
|------|----------------|
| `index.html` | The actual website (text, projects, contact) |
| `styles.css` | Colors, fonts, layout |
| `script.js` | Mobile menu |

No install step. No npm. Just HTML/CSS.

## View it on your computer

```bash
cd portfolio
python3 -m http.server 8080
```

Open http://localhost:8080 in your browser.

## Put it online (GitHub Pages)

1. On GitHub, create a **new empty repo** named exactly: `imoudgil.github.io`
2. Run these commands (repo is already set up locally — skip `git init`):

```bash
cd portfolio
git remote add origin https://github.com/imoudgil/imoudgil.github.io.git
git push -u origin main
```

3. On GitHub: **Settings → Pages → Branch: main → Save**
4. Wait ~1 minute. Your site is live at **https://imoudgil.github.io**

## Important: this repo is NOT your project code

This repo only holds the **website**. Your projects (servkit, GrantPath, etc.) live in **separate GitHub repos**. The website just links to them.

## Edit the site

Change project text or links in `index.html`, then:

```bash
git add .
git commit -m "Update portfolio"
git push
```

The live site updates automatically after a minute.
