# G.I.R. God Is Real Wears — storefront starter

A responsive dark luxury storefront with gold accents, animated hero, product cards, and a working client-side cart.

## Run
Open `index.html` in a browser, or host the folder on Netlify / GitHub Pages.

## Paystack
Checkout currently shows an order preview. To accept real payments, connect Paystack using:
- a Paystack **public** key in the browser,
- a secure server endpoint to initialize transactions,
- server-side verification of the transaction reference before marking an order paid,
- order persistence and stock management.

Never put a Paystack secret key in frontend JavaScript. Product prices and item list are sample values based on the supplied visual. Confirm inventory, sizes, product photography, delivery fees, and final prices with the business before launch.
