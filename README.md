# THOCS Website

Responsive React + Vite frontend for THOCS, using the original supplied THOCS logo and product portfolio artwork.

## Included
- Homepage with five product lines
- Five dedicated product routes: `/products/banta-pop`, `/products/chill-quill`, `/products/mini-mojito`, `/products/strong-soda`, `/products/thocs-energy`
- Interactive flavour search and category filters
- Quick Vibe Check that recommends a product family
- Responsive navigation and accessible focus states
- PIN-code format validation with transparent messaging (a live retailer directory is not connected)
- Client-side route fallback for static hosting in `public/_redirects`
- Product-specific document titles and descriptions

## Local development

```bash
npm install
npm run dev
```

## Production build

```bash
npm run build
npm run preview
```

Vite outputs production assets to `dist/`.

## Render Static Site settings
- Build command: `npm install && npm run build`
- Publish directory: `dist`
- Branch: `main`
- Root directory: leave blank when `package.json` is at repository root

## Important launch notes
- Product artwork is the original artwork supplied for the THOCS project; some images are complete campaign panels rather than isolated pack shots. Replace with approved, high-resolution product photography when available.
- Product prices and pack sizes must be confirmed against current approved packaging before public advertising.
- The PIN-code UI does not yet query a retailer database or claim to return live store availability.
- Social links should be updated to the official THOCS profiles before launch.
