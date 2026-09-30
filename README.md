# Majd Aguir — Portfolio

Personal portfolio of Majd Aguir, AI Engineer & Business Developer (Sousse, Tunisia).

## Structure

- `index.html` — the whole site as a single self-unpacking bundle. The page markup,
  fonts, profile photo and runtime are embedded as JSON in `<script type="__bundler/...">`
  blocks and rebuilt in the browser, so the file needs JavaScript to display.
  Page content lives in the `__bundler/template` block.
- `favicon.png` — site icon.

## Running locally

Open `index.html` in a browser, or serve the folder:

```sh
python3 -m http.server 8000
```

## Editing content

Text is stored as an escaped JSON string inside `index.html`, so edit it with care
(for example with a small script that does exact string replacements) and reload the
page to check it still renders.
