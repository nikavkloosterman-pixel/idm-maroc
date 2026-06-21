# International Destination Management Maroc

Marketing website for **International Destination Management Maroc**, a destination
management company (DMC) that builds full itineraries across Morocco for travellers,
businesses and newlyweds. Operating under **NR1 Commercialisation SARL**.

The site is a single, self-contained static page — no build step, no dependencies.

## View it locally

Open `index.html` in any web browser. That's it.

## What's inside

| Path | Purpose |
| --- | --- |
| `index.html` | The full website (HTML, CSS and JS in one file) |
| `nr1-favicon.svg`, `favicon.ico`, `favicon-*.png` | Browser tab / app icons, referenced by `index.html` |
| `assets/nr1-logo-dark.*` | NR1 Commercialisation logo for dark backgrounds (SVG + PNG) |
| `assets/nr1-logo-light.*` | NR1 Commercialisation logo for light backgrounds (SVG + PNG) |

## Features

- **Trilingual** — switch between English, French and Moroccan Darija (with full
  right-to-left layout for Arabic) using the toggle in the top bar.
- **Responsive** — adapts from desktop down to mobile.
- **Self-contained** — fonts load from Google Fonts; photographs load from Unsplash
  (free for commercial use). Everything else is in the repository.

## Host it for free with GitHub Pages

1. Push this repository to GitHub.
2. In the repository, go to **Settings → Pages**.
3. Under **Build and deployment**, set **Source** to *Deploy from a branch*,
   choose the `main` branch and the `/ (root)` folder, then **Save**.
4. After a minute the site goes live at `https://<your-username>.github.io/<repo-name>/`.

## Editing the contact details, numbers or copy

- Phone and email live in the contact section near the bottom of `index.html`
  (search for `marketingsolutionsmaroc@gmail.com`).
- The legal identifiers are in the footer (search for `180141` / ICE).
- All on-page text for the three languages is in the `I18N` object inside the
  `<script>` block at the end of `index.html`.

## Contact

- Email: marketingsolutionsmaroc@gmail.com
- Phone: +212 784-985173
- Registre de Commerce (RC): 180141
- ICE: 003932513000095
