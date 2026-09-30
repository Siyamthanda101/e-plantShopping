# Paradise Nursery

A React + Redux Toolkit front end for a houseplant shop. Browse plants across three categories,
add them to a cart, adjust quantities, and see live totals.

## Pages
- **Landing page** – company name, About Us paragraph, background image, Get Started button
- **Plants** – 18 plants in 3 categories; Add to Cart disables once added; cart icon shows total items
- **Cart** – thumbnail, name, unit price, per-plant total, +/- buttons, delete, overall totals, Continue Shopping, Checkout ("Coming Soon")

## Key files
`src/App.jsx`, `src/AboutUs.jsx`, `src/App.css`, `src/CartSlice.jsx`, `src/ProductList.jsx`, `src/CartItem.jsx`, `src/store.js`

## Run locally
```
npm install
npm run dev
```

## Deploy to GitHub Pages
```
npm run deploy
```
Then in the repo: Settings → Pages → Source: `gh-pages` branch.
