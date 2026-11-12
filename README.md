# Nearo — local shopping, made simple

A responsive, interactive prototype for a neighborhood shopping platform connecting customers with independent local shops. Built with plain HTML, CSS, and JavaScript — no build step or dependencies required.

## Run locally

Open `index.html` in a browser, or serve the repository root over HTTP:

```bash
python3 -m http.server 4173 --bind 0.0.0.0
```

Then visit `http://localhost:4173`.

## Prototype features

### Customer experience
- Search local stores and products (press **⌘K** / **Ctrl+K** to focus search).
- Browse categories and discover nearby businesses.
- View shop profiles, product selections, opening status, rating, distance and contact details.
- Save shops to favorites, send an enquiry, and call a shop.
- Add items to a persistent cart, adjust quantities, and complete a sample checkout.
- Change the discovery location and view the account/order-history entry point.

### Shop owner studio
- Switch between customer shopping and the separate shop-owner dashboard.
- Sign in to a sample owner account or open the free shop-registration form.
- Add, edit, and remove products; update prices and stock status.
- Review sample orders and move them through the preparation flow.
- Edit shop details and see sample views, orders, rating, and sales metrics.

Cart and inventory changes are saved in browser `localStorage`. Shop/customer registration, enquiries, orders, and account authentication are front-end prototype flows; there is no backend or real payment processing.

## Files
- `index.html` — app markup and content structure
- `styles.css` — responsive design system and layouts
- `app.js` — sample data and interactive behaviors
