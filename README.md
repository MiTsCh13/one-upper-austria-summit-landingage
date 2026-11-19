# One Upper Austria Summit – Landing Page

Static landing page for the One Upper Austria Summit (19 March 2027, Tabakfabrik Linz).

Open `index.html` directly in a browser or serve the folder with any static host (e.g. GitHub Pages). No build step.

- `index.html` – page, styles and scripts (inline)
- `assets/logo.svg` – summit logo
- `assets/favicon.svg`, `assets/apple-touch-icon.png` – favicon built from the logo's "O" mark
- `assets/organisations/` – logos of participating organisations (trimmed, max. 240 px high)

## Interest form

"Confirm your interest" / "Join as partner" open a form dialog. Submissions are sent via [FormSubmit](https://formsubmit.co) to the address in `FORM_ENDPOINT` (script at the bottom of `index.html`).
The very first submission triggers a one-time activation email to that address; submissions are only delivered after clicking the activation link.
