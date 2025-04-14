# 🛒 Shopping Web App - Front-End Internship Project

A responsive shopping website built with **React.js**, integrating the [Fake Store API](https://fakestoreapi.com/). Developed as part of a front-end internship assignment.

---

## 🚀 Live Demo

👉 [View Live Site Here](https://your-live-vercel-link.vercel.app)  
👉 [GitHub Repository](https://github.com/your-username/shopping-site)

---

## 📋 Assignment Requirements

### ✅ Features Implemented:
- 🔐 **Login Page**:
  - Authenticate using Fake Store API’s `/auth/login`
  - Store JWT in `localStorage`
  - Redirect to product listing on successful login
- 🏬 **Product Listing Page (Home)**:
  - Fetch and display products using `/products`
  - Filter by category via `/products/category/:category`
  - Mobile-first responsive grid layout
- 📄 **Product Detail Page**:
  - Show product image, title, description, price
  - "Add to Cart" functionality
- 🛒 **Cart Page**:
  - View added products with quantity & remove options
  - Calculate total price
  - Checkout clears cart and shows a 4-second popup confirmation
- 🧭 **Header/Navigation**:
  - Links: Home | Cart | Logout
  - Cart item count displayed
  - Logout clears JWT and redirects to login

---

## 🛠 Tech Stack

- **React.js**
- **React Router v6**
- **React Hooks**
- **Axios**
- **Context API** (for cart state)
- **Plain CSS** (mobile-first responsive design)

---

## 🔐 Test Login Credentials

Use these credentials (provided by Fake Store API):

```json
{
  "username": "mor_2314",
  "password": "83r5^_"
}
