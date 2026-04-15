Project: Maple & Co. Realty (course website)

Files created:
- index.html — professional Bootstrap site with resume section
- scratch.html — from-scratch page (no Bootstrap) with nested lists, images, YouTube embed, on-page anchor, custom stylesheet, and Tableau embed
- scratch.css — custom stylesheet (font family, colors, 4+ definitions, 3 positioned divs)
- app_guess.html — small single-page number guessing web app

Next steps to host on GitHub Pages:
1. Initialize a git repo in the project folder:

```bash
cd "final project"
git init
git add .
git commit -m "Initial site files"
```

2. Create a GitHub repository (via web UI) named e.g. `final-project-site` and add it as remote:

```bash
git remote add origin https://github.com/YOUR_USERNAME/final-project-site.git
git branch -M main
git push -u origin main
```

3. In the GitHub repo settings, enable GitHub Pages and set the source to `main` branch (root). The site will be published at `https://YOUR_USERNAME.github.io/final-project-site/`.

Notes:
- `scratch.html` includes an embedded Tableau Public iframe pointing to a public sample workbook. If the viz fails to load, replace the iframe src with a Tableau Public URL you choose.
- All external image and social links point to stable public sites; verify after publishing and update if you want personal links.

If you want, I can:
- Commit and create the repo for you (I need GitHub access/credentials)
- Replace the Tableau embed URL with one you prefer
- Add more pages or polish styling
