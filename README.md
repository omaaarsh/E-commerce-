# 👗 Wearly Frontend

Welcome to **Wearly**, a modern clothing e-commerce platform frontend!

Built with **HTML, CSS, JavaScript, and Bootstrap**, it connects to a robust backend to deliver a fully dynamic shopping experience — from browsing products to managing carts, wishlists, and profiles.

---

## 🌐 Live Demo

🚀 **Try it live** (when deployed):  
[🔗 Wearly Frontend Live](https://your-demo-link.com) *(Replace with your deployment URL)*

---

## 🏗 Code Structure

| File / Folder     | Description                                                            |
|--------------------|------------------------------------------------------------------------|
| `index.html`      | Homepage: category navigation, highlights, API-driven content.         |
| `men.html`        | Men’s category page, populated via API.                               |
| `women.html`      | Women’s category page, loaded dynamically.                           |
| `kids.html`       | Kids/Baby category page, sourced from APIs.                          |
| `product.html`    | Product details page with dynamic content.                           |
| `cart.html`       | Shopping cart synced to backend.                                     |
| `login.html`      | User login page, connected to authentication API.                    |
| `signup.html`     | User signup page, posting registration data.                         |
| `profile.html`    | User profile page, fetching and updating user data.                  |
| `photos/`        | Product images and media assets.                                     |
| `.vscode/`       | Development settings for VS Code.                                    |

---

## ⚙ Technologies Used

![HTML5](https://img.shields.io/badge/HTML5-orange?logo=html5)  
![CSS3](https://img.shields.io/badge/CSS3-blue?logo=css3)  
![JavaScript](https://img.shields.io/badge/JavaScript-yellow?logo=javascript)  
![Bootstrap](https://img.shields.io/badge/Bootstrap-purple?logo=bootstrap)

---

## 🔌 API Integration Overview

| Feature        | Endpoint                                           |
|---------------|-----------------------------------------------------|
| **Products**  | `GET /api/v1/products`, `GET /api/v1/products/{id}` |
| **Categories**| `GET /api/v1/categories`                            |
| **Accounts**  | `POST /api/v1/accounts/register` <br> `POST /api/v1/accounts/login` <br> `GET /api/v1/accounts/profile` <br> `POST /api/v1/accounts/logout` |
| **Cart**      | `GET /api/v1/cart` <br> `POST /api/v1/cart/add` <br> `POST /api/v1/cart/remove` |
| **Wishlist**  | `GET /api/v1/wishlist` <br> `POST /api/v1/wishlist/add` <br> `POST /api/v1/wishlist/remove` |

📖 **API Documentation** (backend): [View API Docs](https://github.com/omaaarsh/Wearly-Backend-Repo-Link) *(Replace with backend repo or docs link)*

---

## ✨ Interactive Features

✅ Dynamic product loading  
✅ Live cart and wishlist updates  
✅ User login/signup with session management  
✅ Responsive Bootstrap layout  
✅ Interactive icons (wishlist ❤️, cart 🛍, profile 👤)  
✅ Real-time API error handling (alerts & UI updates)

---

## 🛠 Setup Instructions

### 1️⃣ Clone the repository
```bash
git clone https://github.com/omaaarsh/Wearly-Clothing-ECommerce-front-end-.git
