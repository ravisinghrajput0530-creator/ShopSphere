# ShopSphere – React E-Commerce Frontend

A frontend-only educational shopping application created with React, JavaScript, HTML and CSS.

## Features
- Responsive shopping home page
- Product search by name, category and description
- Category filters
- Add products to cart
- Increase/decrease quantity and remove items
- Cart count and subtotal
- Cart data saved in browser LocalStorage

## Requirements
- Node.js (LTS recommended)
- npm
- VS Code (recommended)

## Run the project
1. Extract the ZIP file.
2. Open the `ShopSphere_React` folder in VS Code.
3. Open the terminal in that folder.
4. Run:

```bash
npm install
npm run dev
```

5. Open the local URL printed by Vite (usually `http://localhost:5173`).

## Build for production
```bash
npm run build
```

## Important project scope
This is a frontend demo. It does not include a server, database, real user authentication, payment gateway or real order processing. Product data is stored in `src/data/products.js`. Cart data is stored locally in the browser.

## Customize products
Edit `src/data/products.js`. Each product has an id, name, category, price, oldPrice, rating, badge, image and description.
