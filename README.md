# Portfolio

Personal portfolio of Alvin James Agot, Go developer at Zone01 Kisumu.

Plain HTML and CSS. No build step, no dependencies. Fonts load from Google Fonts.

## Structure

```
portfolio/
├── index.html          page content
├── css/
│   └── style.css       all styles, light and dark theme
├── assets/
│   └── images/
│       ├── profile.jpg
│       └── keepsafe-overview.jpg
├── README.md
└── .gitignore
```

## Run locally

Open `index.html` in a browser, or serve the folder:

```
python3 -m http.server 8000
```

## Deploy on GitHub Pages

1. Push this folder to the `main` branch of `alvinjames-max/portfolio`.
2. Go to Settings, then Pages, and set the source to `main` and `/ (root)`.
3. The site goes live at `https://alvinjames-max.github.io/portfolio/`.

## Edit

- Content and projects: the `<article class="proj">` blocks in `index.html`.
- Colors and layout: `css/style.css`. Colors are variables at the top.
- Images: replace the files in `assets/images/` and keep the same names.
