# Portfolio of a Foreign Language Teacher

Personal portfolio website of Irina Zhuravleva, a foreign language teacher (English, Spanish, French).

## About

A single-page bilingual (RU/EN) website with a collage-style design. Sections:

- **About** — teaching approach and key figures
- **Languages** — which languages I teach and how
- **Experience** — work experience and education
- **Certificates** — a gallery of certificates with category filters
- **Contact** — how to get in touch

## Tech

A static site built with HTML, CSS and a bit of vanilla JavaScript. No build step, no dependencies.

## Run locally

Open `index.html` in your browser, or start a local server:

```bash
python3 -m http.server 8000
```

Then go to http://localhost:8000.

## Deploy

The site can be hosted on GitHub Pages: **Settings → Pages → Deploy from a branch → `main` / root**.

## Structure

```
index.html        — page, styles and scripts
certificates/     — certificate images
*.svg, *.jpeg     — decorations and illustrations
```
