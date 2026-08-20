# 🛒 Simple E-Commerce Store

A basic full-stack e-commerce web application developed as **Task 1** of the web development project.

The application allows users to browse products, view product details, add products to a shopping cart, register/login, and place orders.

## ✨ Features

- 🛍️ Product listings
- 🔎 Product details
- 🛒 Shopping cart
- ➕ Add products to cart
- ➖ Update/remove cart items
- 📦 Order processing
- 👤 User registration
- 🔐 User login
- 💾 Database storage
- 📱 Responsive design

## 🛠️ Technologies Used

### Frontend
- HTML5
- CSS3
- JavaScript
- Bootstrap 5

### Backend
- Node.js
- Express.js

### Database
- MongoDB

## 📂 Project Structure

```text
ecommerce-store/
│
├── public/
│   ├── index.html
│   ├── products.html
│   ├── product-details.html
│   ├── cart.html
│   ├── login.html
│   └── register.html
│
├── css/
│   └── style.css
│
├── js/
│   ├── app.js
│   ├── products.js
│   ├── cart.js
│   └── auth.js
│
├── models/
│   ├── Product.js
│   ├── User.js
│   └── Order.js
│
├── routes/
│   ├── productRoutes.js
│   ├── userRoutes.js
│   └── orderRoutes.js
│
├── server.js
├── package.json
├── .env.example
└── README.md
