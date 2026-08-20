# ShopSphere E-commerce Store

ShopSphere is a beginner-friendly e-commerce website built with Node.js, Express, MongoDB, and plain HTML/CSS/JavaScript. It includes user authentication, product listing, cart management, checkout, and order tracking for a college project.

## Features

- Responsive homepage with product listing and filters
- Product detail page
- Shopping cart with quantity controls
- User registration and login with secure password hashing
- JWT-based authentication for protected routes
- Checkout form and order creation
- My Orders page for logged-in users
- MongoDB-ready models and demo fallback mode
- Clean and modern UI using Bootstrap 5

## Tech Stack

- Frontend: HTML5, CSS3, Vanilla JavaScript, Bootstrap 5
- Backend: Node.js, Express.js
- Database: MongoDB, Mongoose
- Authentication: JWT + bcryptjs

## Folder Structure

```bash
ecommerce-store/
├── data/
│   └── sampleProducts.js
├── middleware/
│   └── authMiddleware.js
├── models/
│   ├── User.js
│   ├── Product.js
│   └── Order.js
├── public/
│   ├── css/
│   │   └── style.css
│   ├── js/
│   │   ├── app.js
│   │   ├── auth.js
│   │   ├── cart.js
│   │   ├── checkout.js
│   │   ├── orders.js
│   │   └── products.js
│   ├── index.html
│   ├── product.html
│   ├── cart.html
│   ├── login.html
│   ├── register.html
│   ├── checkout.html
│   ├── orders.html
│   └── success.html
├── routes/
│   ├── authRoutes.js
│   ├── productRoutes.js
│   └── orderRoutes.js
├── .env.example
├── .gitignore
├── package.json
├── server.js
└── README.md
```

## Installation

1. Open the project folder.
2. Run:

```bash
npm install
```

3. Copy `.env.example` to `.env` and update values.

## MongoDB Setup

- Install MongoDB locally or use MongoDB Atlas.
- Set `MONGODB_URI` in your `.env` file.
- Example:

```env
MONGODB_URI=mongodb://127.0.0.1:27017/shopSphere
JWT_SECRET=your_secret_key
PORT=3000
```

## Environment Variables

```env
PORT=3000
MONGODB_URI=mongodb://127.0.0.1:27017/shopSphere
JWT_SECRET=your_secret_key
```

## Run the Project

```bash
npm start
```

Open the browser at:

```text
http://localhost:3000
```

## API Endpoints

### Products

- `GET /api/products`
- `GET /api/products/:id`

### Authentication

- `POST /api/auth/register`
- `POST /api/auth/login`
- `POST /api/auth/logout`
- `GET /api/auth/me`

### Orders

- `GET /api/orders`
- `POST /api/orders`
- `GET /api/orders/:id`

## Screenshots

Add screenshots here later for the project demo.

## Notes

This project is designed to be simple and beginner-friendly. A sample product catalog is loaded automatically, and the application is designed to work even when a MongoDB server is not available yet by falling back to demo data.
