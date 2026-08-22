# 🛒 JavaScript Amazon Clone Project

A functional e-commerce web application inspired by Amazon. Built with vanilla **JavaScript**, **HTML**, and **CSS** to demonstrate modern frontend web development, OOP concepts, unit testing, async workflows, and backend API interactions.

---

## 🌟 Features

* **Product Catalog:** Dynamic rendering of products, ratings, pricing, and options from data models / API endpoints.
* **Interactive Shopping Cart:**
  * Add products to cart with quantity selectors.
  * Real-time header cart count updates.
  * Update quantities or remove items directly on the checkout page.
* **Dynamic Checkout & Delivery:**
  * Selectable delivery options (Free, Standard, Express) that instantly re-calculate estimated delivery dates.
  * Live Order Summary calculation (Items subtotal, Shipping & Handling, Estimated Tax, Total).
* **Order Placement & History:** Place orders and view order history with tracking details (`orders.html` and `tracking.html`).
* **Search Functionality:** Filter products based on search queries.
* **Testing:** Modular design covered by automated unit and integration tests using **Jasmine**.

---

## 🛠️ Tech Stack & Concepts

* **Frontend:** HTML5, CSS3, JavaScript (ES6 Modules)
* **Testing Framework:** Jasmine
* **Key JS Concepts Implemented:**
  * Document Object Model (DOM) Manipulation
  * Event Listeners & Event Delegation
  * ES Modules (`import` / `export`)
  * Object-Oriented Programming (OOP) & Classes
  * Promises, Fetch API, and `async/await`
  * Data Persistence using `localStorage`
  * External libraries (`dayjs` for date formatting)

---

## 📂 Project Structure

```text
javascript-amazon-project/
├── backend/            # Backend data / Mock API files
├── data/               # Data models (cart.js, products.js, deliveryOptions.js)
├── images/             # Product images, icons, and ratings graphics
├── scripts/            # Core JavaScript files
│   ├── checkout/       # Checkout modular scripts (orderSummary, paymentSummary)
│   ├── utils/          # Utility functions (currency formatting)
│   ├── amazon.js       # Homepage interactive logic
│   ├── checkout.js     # Checkout page interactive logic
│   ├── orders.js       # Order history logic
│   └── tracking.html   # Package tracking page logic
├── styles/             # Modular CSS stylesheets (pages, shared components)
├── tests/              # Jasmine test scripts and test runners
├── amazon.html         # Main storefront view
├── checkout.html       # Cart review and payment page
├── orders.html         # Past orders page
└── tracking.html       # Delivery status page
