# THOCS Website — Product Pages Update

React + Vite website for the THOCS beverage portfolio, retaining the supplied THOCS logo and product artwork.

## Run locally

```bash
npm install
npm run dev
```

## Production build

```bash
npm run build
npm run preview
```

## Product pages

- `/products/banta-pop`
- `/products/chill-quill`
- `/products/mini-mojito`
- `/products/strong-soda`
- `/products/thocs-energy`

The product cards and footer links open the matching product page. Browser back/forward navigation is supported.

## Deploy on Render

Use a **Static Site** with:

- Build command: `npm install && npm run build`
- Publish directory: `dist`
- Root directory: blank (assuming `package.json` is at repository root)

For direct visits and refreshes on product URLs, add a Render rewrite rule in the Static Site dashboard:

- Source: `/*`
- Destination: `/index.html`
- Action: `Rewrite`

The `public/_redirects` file is included for hosts that support this convention; Render's dashboard rewrite rule is the important fallback for direct nested-route requests.

## Content accuracy

Product flavours and pack details are transcribed from the user-provided THOCS portfolio PDF. The source artwork lists:

- Mini Mojito: Watermelon, Litchi, Mint, Blueberry; 160 ml ₹10 and 300 ml ₹20.
- Chill Quill: Lemon Masala and Jeera Masala; 160 ml ₹10 and 300 ml ₹20.
- Banta Pop: Masala Cola, Pineapple Masala, Mango Masala, Lemon Masala; supplied creative shows 250 ml ₹50.
- THOCS Energy: Classic Energy, Tropical Punch, Berry Blast, Citrus Blast; supplied creative shows 250 ml ₹60.
- Strong Soda: 300 ml ₹10.

Confirm prices and pack sizes with the business before public commercial use.

## Important

The PIN-code store finder remains a prototype and does not query a live stockist database. Do not present its confirmation as proof of local availability.
