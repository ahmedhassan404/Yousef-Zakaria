# Ecommerce Store API

The Ecommerce Store API is a robust and scalable backend solution for managing e-commerce operations. It provides RESTful endpoints to handle user authentication, product catalog management, and order processing. Built using Node.js, Express.js, and MongoDB, the API is modular, secure, and production-ready.

---

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Getting Started](#getting-started)
- [Environment Configuration](#environment-configuration)
- [API Endpoints](#api-endpoints)
- [Project Structure](#project-structure)
- [Testing](#testing)
- [Contributing](#contributing)
- [License](#license)

---

## Overview

This project serves as the backend of an e-commerce platform. It enables the creation and management of users, products, and orders with full CRUD support and secure authentication. The API is well-suited for single-page applications (SPAs), mobile apps, or admin dashboards.

---

## Features

- JWT-based user authentication
- Role-based access control for admins
- CRUD operations for products and orders
- Secure password handling with bcrypt
- Error handling and validation middleware
- MongoDB integration with Mongoose
- Modular and maintainable folder structure

---

## Tech Stack

- **Backend Framework**: Node.js with Express.js
- **Database**: MongoDB (via Mongoose)
- **Authentication**: JSON Web Tokens (JWT)
- **Security**: bcrypt, helmet, CORS
- **Development Tools**: nodemon, dotenv, ESLint

---

## Getting Started

### Clone the Repository

bash
git clone https://github.com/Abdulrhman-Gawish/ecommerce-store-api.git
cd ecommerce-store-api
Install Dependencies
bash
npm install
Run the Development Server
bash
npm run dev
The server will start on http://localhost:5000.

Environment Configuration
Create a .env file in the root directory and define the following variables:

env
PORT=5000
MONGODB_URI=mongodb://localhost:27017/ecommerce
JWT_SECRET=your_secret_key
API Endpoints
Authentication
Method	Route	Description
POST	/api/auth/register	Register a new user
POST	/api/auth/login	Login and receive JWT
Products
Method	Route	Description
GET	/api/products	Get all products
GET	/api/products/:id	Get product by ID
POST	/api/products	Create new product
PUT	/api/products/:id	Update product by ID
DELETE	/api/products/:id	Delete product by ID
Orders
Method	Route	Description
GET	/api/orders	Get all orders
GET	/api/orders/:id	Get order by ID
POST	/api/orders	Create a new order
PUT	/api/orders/:id	Update order status
DELETE	/api/orders/:id	Cancel/delete an order
Project Structure
ecommerce-store-api/
│
├── config/               # Database connection
├── controllers/          # Business logic
├── middleware/           # Auth, error handling
├── models/               # Mongoose models
├── routes/               # Express route handlers
├── utils/                # Utility functions
├── .env                  # Environment variables
├── server.js             # App entry point
├── package.json          # Project metadata
└── README.md             # Project documentation
Testing
To run automated tests (if configured):

bash
npm test
You may use tools like jest, supertest, or mocha for API testing.

Contributing
Fork the repository

Create your feature branch: git checkout -b feature/feature-name

Commit your changes: git commit -m 'Add new feature'

Push to the branch: git push origin feature/feature-name

Submit a pull request

Please ensure your code adheres to project standards and passes linting rules.
