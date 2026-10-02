# Majd Aguir — Portfolio

Personal portfolio of Majd Aguir, AI & Data Science Engineer (Sousse, Tunisia).

## Structure

- `index.html` — the whole site: plain HTML with inline CSS and a small script for the
  light/dark toggle, the "Copy Email" button and scroll-in animations. No build step.
- `avatar.jpg` — profile photo shown in the hero card.
- `favicon.png` — site icon.
- `og-image.png` — 1200×630 preview image shown when the link is shared.

Live at https://majd-aguir.vercel.app (deployed by Vercel on every push to `main`).
The old GitHub Pages address, majd1029.github.io/portfolio, redirects there.

The Inter font loads from Google Fonts; everything else is local.

## Running locally

Open `index.html` in a browser, or serve the folder:

```sh
python3 -m http.server 8000
```

## Editing content

Edit the text directly in `index.html`. Sections are marked with comments
(`Hero bento`, `About`, `Projects`, `Experience`, `Education`, `Contact`), and colours
for both themes are defined as CSS variables at the top of the `<style>` block.
