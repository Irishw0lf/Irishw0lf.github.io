# Brendin Eaton — Portfolio

Static site. No build step, no dependencies.

- `index.html` — the whole page (styles and script inline)
- `img/` — 57 JPEGs
- `.nojekyll` — tells GitHub Pages to serve files as-is

## Run locally
Any static server. For example:
    npx serve .

## Contact form
The form composes an email and hands it to the visitor's mail app.
To send server-side instead, set ONE line near the bottom of `index.html`:

    var ENDPOINT = "";   // e.g. https://formsubmit.co/YOUR@EMAIL

Leave it empty and the mail-app path stays.
