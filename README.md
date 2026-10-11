# THOCS Homepage — Polished Prototype

Responsive React + Vite homepage prototype for THOCS, using the supplied original logo and product portfolio artwork.

## Requirements
- Node.js LTS (includes npm)

## Run locally
1. Extract the ZIP.
2. Open Terminal in the `thocs-homepage` folder.
3. Run:

```bash
npm install
npm run dev
```

4. Open the local URL printed by Vite (normally http://localhost:5173).

## Production build
```bash
npm run build
npm run preview
```

## Included interactions
- Responsive navigation and mobile menu
- Product category filters and flavour search
- Product detail dialogs
- PIN-code format validation in the store-finder dialog
- Smooth navigation and reduced-motion support
- Keyboard focus indicators

## Important limitations
The store finder validates the six-digit PIN format but does not yet query a live retailer/distributor database. Product artwork is sourced from the supplied THOCS reference PDF; individual crops are used as image panels. Confirm packaging, pricing, claims, legal text, and final product photography before launch.
