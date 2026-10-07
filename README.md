# Laptop Lab

A responsive, localized laptop storefront built with plain HTML, CSS, and JavaScript. It includes generated laptop product photography, Uzbek/Russian/English copy, light and dark themes, product search and filters, quick views, a persistent demo cart, and a newsletter interaction.

## Run locally

From the repository root, start any static file server. For example:

```bash
python3 -m http.server 4173 --bind 0.0.0.0
```

Then open `http://localhost:4173` in a browser. No build step or external JavaScript packages are required.

## Project files

- `index.html` — page structure and accessible UI controls
- `styles.css` — responsive layout, liquid-glass surfaces, soft UI cards, and dark theme
- `app.js` — translations and storefront interactions
- `assets/images/` — generated laptop imagery used in the hero, product cards, and promotion

Cart, language, theme, and favorites are saved in the browser's local storage. Checkout and newsletter submission are demo-only and do not send data to a backend.
