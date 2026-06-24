# Tyrone Chiropractic Clinic

Marketing website for Tyrone Chiropractic Clinic — St. Petersburg, FL.

A static, single-page site built with plain HTML and CSS (no build step required).

## Structure

```
.
├── index.html        # Home page (the entry point)
├── css/
│   └── styles.css    # All site styles
└── README.md
```

## Running locally

Because it's a static site, just open the file in a browser:

```sh
open index.html
```

Or serve it with any static server (recommended, so relative paths resolve like in production):

```sh
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Deploying with GitHub Pages

1. Push this repository to GitHub.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, set **Source** to *Deploy from a branch*.
4. Choose the `main` branch and the `/ (root)` folder, then **Save**.

GitHub Pages serves `index.html` automatically, so the site will be live at
`https://<username>.github.io/<repository>/`.

## Notes

- Fonts are loaded from Google Fonts; appointment booking links point to Zocdoc.
- Update clinic details (hours, phone, address) directly in `index.html`.
