# Iyaj Uddin Parosh — Portfolio

A short, premium dark portfolio built with plain HTML, CSS, and JavaScript.

## Structure

```
portfolio/
├── index.html
├── assets/
│   ├── css/style.css
│   ├── js/script.js
│   └── images/profile.jpg   (add your own photo here)
└── README.md
```

## Run locally

No build step is needed. Just open `index.html` in a browser, or serve the
folder with any static server, e.g.:

```bash
python3 -m http.server 8000
```

then visit `http://localhost:8000`.

## Add your photo

Drop a photo at `assets/images/profile.jpg`. If the file is missing, the hero
automatically shows a gradient initials avatar instead, so the site still
looks complete without it.

## Deploy to GitHub Pages

1. Push this folder's contents to the root of your
   `iyajuddinparosh.github.io` repository (or any repository, then enable
   Pages for it).
2. In the repository, go to **Settings → Pages**, set the source branch to
   `main` and the folder to `/ (root)`.
3. Your site will be live at `https://iyajuddinparosh.github.io/`.

## Custom domain (`iyajuddin.pro.bd`)

1. Add a `CNAME` file at the project root containing:
   ```
   iyajuddin.pro.bd
   ```
2. At your DNS provider, point the domain to GitHub Pages (a `CNAME` record
   to `iyajuddinparosh.github.io`, or the GitHub Pages `A` records for an
   apex domain).
3. In **Settings → Pages**, add the custom domain and enable **Enforce
   HTTPS** once DNS has propagated.

## Notes

- No frameworks — vanilla HTML/CSS/JS, plus Font Awesome and AOS from a CDN.
- All content reflects only the information provided; future projects are
  clearly marked "Coming Soon".
