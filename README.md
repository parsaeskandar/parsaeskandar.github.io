# parsaeskandar.github.io

Single-page personal site. No build step, no dependencies.

## Files

- `index.html` — the whole site (HTML + CSS inline)
- `cv.pdf` — your CV, linked from the header
- `photo.jpg` — optional square headshot (hidden automatically if missing)

## Deploy (one time)

1. On GitHub, create a new **public** repository named exactly `parsaeskandar.github.io`.
2. In this folder:

   ```bash
   git init
   git add index.html cv.pdf photo.jpg README.md
   git commit -m "Personal site"
   git branch -M main
   git remote add origin git@github.com:parsaeskandar/parsaeskandar.github.io.git
   git push -u origin main
   ```

3. Wait about a minute, then open https://parsaeskandar.github.io

GitHub Pages serves the `main` branch of a `<username>.github.io` repo automatically;
no settings to change.

## Update

Edit `index.html`, replace `cv.pdf`, commit, push. Live within a minute.

## Custom domain (optional)

Buy a domain, add a file named `CNAME` containing just the domain
(e.g. `parsaeskandar.com`), push, and point the domain's DNS at GitHub Pages
per https://docs.github.com/pages/configuring-a-custom-domain-for-your-github-pages-site.
