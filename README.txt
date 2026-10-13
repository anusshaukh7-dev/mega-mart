# Mega Mart — free static storefront starter

## Files
- `index.html`: storefront, cart, checkout and admin interface
- `style.css`: responsive design for mobile and desktop
- `products.js`: 180 demo products with sample image URLs
- `app.js`: search, category filters, cart, product admin, delivery settings, JSON backup and WhatsApp order draft

## Publish with GitHub Pages
1. Sign in to GitHub and open your repository.
2. Upload these four files (`index.html`, `style.css`, `products.js`, `app.js`) to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/(root)`, then save.
5. Wait for GitHub to provide your public website URL.

## Important limitations before real sales
This is a front-end demo that can be hosted free on GitHub Pages. The admin tool stores edits in the current browser's local storage, not in a shared database. It is useful for a demo and same-device testing, but edits do not automatically appear on other devices or for all customers. The checkout prepares an order message in WhatsApp; add your real WhatsApp number in **Admin → Store settings**. Delivery charges are estimates shown in the WhatsApp order draft.

Before accepting real orders, connect a secure database/backend (for example, a free-tier hosted database), protect admin access, verify product images and prices, and test orders. Never put secret keys or passwords in public JavaScript. A future mobile app can reuse a shared backend/API.
