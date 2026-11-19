# Flipmart

A modern, responsive e-commerce storefront built with **React** and **Vite**. Flipmart offers a complete client-side shopping experience featuring product browsing, persistent cart and wishlist management, buyer profile storage, and a multi-step checkout interface.

🔗 **Live Demo:** [fipmart.vercel.app](https://fipmart.vercel.app/)

---

## ✨ Features

- **Product Browsing & Animations:** Interactive storefront UI with smooth transitions and locally served product imagery (`public/images`).
- **Persistent Cart & Wishlist:** Add, update, or remove items from your shopping cart and wishlist with browser-backed state persistence.
- **Buyer Profile Management:** Save and manage user account and shipping details directly in the browser.
- **Checkout Interface:** End-to-end checkout flow UI for reviewing orders and shipping summaries.
- **Responsive Design:** Adaptive layout tailored for desktop, tablet, and mobile viewports.

---

## 🛠️ Tech Stack

- **Frontend:** React, JavaScript (ES6+), CSS3, HTML5
- **Build Tool & Linter:** Vite, ESLint
- **Deployment:** Vercel

---

## 📂 Project Structure

```text
flipmart/
├── public/
│   └── images/             # Locally served product and UI assets
├── src/                    # Application components, state logic, and styles
├── .gitignore              # Git ignore rules
├── eslint.config.js        # ESLint configuration
├── index.html              # HTML entry template
├── package.json            # Dependencies and npm scripts
├── vercel.json             # Vercel routing and deployment configuration
└── vite.config.js          # Vite bundler configuration
