# MasumCart

Responsive fashion e-commerce **demo storefront** built with HTML5, CSS3 and vanilla JavaScript.

## Features
- Responsive men/women catalog using six original product images
- Working search, category filtering and price/name sorting
- Local wishlist and shopping bag with quantity controls and subtotal
- Browser localStorage persistence (per browser)
- Accessible labels, keyboard-operated controls, cart dialog and reduced-motion support

## Quick start
Open `index.html` locally or start a local HTTP server: `python -m http.server 8000`.

## Structure
- `index.html` — storefront and cart dialog
- `assets/css/style.css` — design and responsive layouts
- `assets/js/app.js` — demo product data, filtering, cart and wishlist
- `Assets/` — existing original product pictures
- `LICENSE` — MIT

The older empty category pages and local Bootstrap distribution remain in the repo for backward compatibility but are no longer needed by the redesigned homepage. Future cleanup can remove them after verifying any external links.

## Scope and limitations
This is **not a live commerce site**. Original sample USD prices are retained. There is no inventory verification, authentication, payment integration, shipping, orders or backend. Do not enter payment details. Cart/wishlist persist only in your current browser.

## Deploy
Use GitHub Pages (Settings → Pages → Deploy from branch → `main` / root) after merging the upgrade PR. Relative asset paths work on project Pages URLs.

## Author
Masum Billah — [GitHub](https://github.com/gitwithmasum)

## License
MIT. See [LICENSE](LICENSE).
