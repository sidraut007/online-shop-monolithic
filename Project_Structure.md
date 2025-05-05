
## Project Structure 📁

```
.
├── CONTRIBUTING.md
├── LICENSE
├── README.md
├── ROADMAP.md
├── eslint.config.js
├── index.css
├── index.html
├── package-lock.json
├── package.json
├── public
│   ├── OS.svg
│   └── imgs
│       ├── logo.png
│       ├── logo.svg
│       └── placeholder-image.png
├── src
│   ├── App.jsx
│   ├── bootstrap-overrides.scss
│   ├── components
│   │   ├── CartItem.jsx
│   │   ├── DeleteProductModal.jsx
│   │   ├── Footer.jsx
│   │   ├── InProgressToastContent.jsx
│   │   ├── LoadingSpinner.jsx
│   │   ├── Modals
│   │   │   ├── CheckoutModal.jsx
│   │   │   ├── DeleteProductModal.jsx
│   │   │   ├── NewProductModal.jsx
│   │   │   └── UpdateProductModal.jsx
│   │   ├── Navbar.jsx
│   │   ├── ProductItem.jsx
│   │   ├── SearchBar.jsx
│   │   ├── ShoppingCart.jsx
│   │   ├── Store.jsx
│   │   ├── StoreItem.jsx
│   │   ├── ThemeToggle.jsx
│   │   └── UpdateProductModal.jsx
│   ├── context
│   │   ├── NavBarContext.jsx
│   │   ├── ShoppingCartContext.jsx
│   │   ├── ShoppingItemsContext.jsx
│   │   └── ThemeContext.jsx
│   ├── data
│   │   ├── demoProducts.js
│   │   └── productData.js
│   ├── hooks
│   │   └── useLocalStorage.js
│   ├── index.css
│   ├── main.jsx
│   ├── pages
│   │   ├── Admin.jsx
│   │   ├── Checkout.jsx
│   │   ├── Home.jsx
│   │   └── Store.jsx
│   ├── services
│   │   └── db.js
│   └── utilities
│       └── formatCurrency.js
└── vite.config.js
```

### Prerequisites

- Node.js (v16 or higher)
- npm or yarn
- Git

### Setting Up Development Environment
```bash
Port: 3000
```


1. Install dependencies:
```bash
npm install
# or
yarn install
```

2. Start development server:
```bash
npm run dev
# or
yarn dev
```


