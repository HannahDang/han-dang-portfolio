# Han Dang — Portfolio

A single-file static site (`index.html`, no build step) for Han Dang's product management portfolio.

## Preview locally

Open `index.html` directly in a browser, or serve it:

```bash
cd han-dang-portfolio
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Deploy to GitHub Pages

1. Create a new repository on GitHub (e.g. `han-dang-portfolio`), don't initialize it with a README.
2. From this folder, push it:

   ```bash
   git remote add origin https://github.com/<your-username>/han-dang-portfolio.git
   git branch -M main
   git push -u origin main
   ```

3. On GitHub: go to the repo's **Settings → Pages**, set **Source** to `Deploy from a branch`, branch `main`, folder `/ (root)`, then save.
4. Your site will be live at `https://<your-username>.github.io/han-dang-portfolio/` within a minute or two.

### Using a custom domain

Add a `CNAME` file to this folder containing just your domain (e.g. `handang.dev`), and point your DNS `A`/`CNAME` records at GitHub Pages per [GitHub's custom domain docs](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site).
