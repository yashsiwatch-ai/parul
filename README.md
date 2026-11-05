# Lumina Beauty — Cosmetic Store Frontend

Assessment: **Frontend Deployment on Vercel**

A responsive React storefront for cosmetics, skincare, fragrance, and jewellery. Users can browse products, open details, add items to the cart, update quantities, and complete a demo checkout.

## Features

- Responsive layout for desktop, tablet, and mobile
- Product listing with search and category filters
- Product detail page
- Cart with quantity controls, tax, and totals
- Demo checkout (no PayPal account required)
- About page, 404 page, and sticky navigation with cart badge

## Project structure

```
src/
  components/     UI screens and reusable pieces
  components/Cart Cart table, totals, and empty state
  context.js      Product and cart state
  data.js         Product catalog
public/img/       Product images
vercel.json       Vercel build and SPA routing
SUBMISSION.txt    Links required by the assessment
```

## Local development

```bash
npm install
npm start
```

Open [http://localhost:3000](http://localhost:3000).

Production build:

```bash
npm run build
```

## Vercel settings

When importing the GitHub repository into Vercel:

- Framework preset: **Create React App**
- Build command: `npm run build`
- Output directory: `build`

`vercel.json` already sets these values and rewrites routes to `index.html` so `/details`, `/cart`, and `/about` work on refresh.

## Deploy steps (assessment)

1. Create a public GitHub repository.
2. Push this project to GitHub from this folder.
3. Sign in to [Vercel](https://vercel.com) with GitHub.
4. Import the repository.
5. Confirm the settings above and deploy.
6. Open the live URL and test products, cart, and checkout.
7. Paste both public links into `SUBMISSION.txt`.

## Submission file

`SUBMISSION.txt` must contain:

1. Live Deployment Link (Vercel URL)
2. GitHub Repository Link
