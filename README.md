# Inventory Management System

A REST API for managing product inventory using Node.js, Express.js, MongoDB, and Mongoose.

## Features

- Create a new product
- Get all products
- Purchase a product
- Restock a product
- View product transaction history
- Product name uniqueness validation
- Price validation
- Stock validation
- Purchase stock availability validation
- Purchase and restock transaction records

## Technologies Used

- Node.js
- Express.js
- MongoDB
- Mongoose
- dotenv

## Project Structure

```text
inventory-management/
│
├── controllers/
│ └── productController.js
│
├── models/
│ ├── Product.js
│ └── Transaction.js
│
├── routes/
│ └── productRoutes.js
│
├── .env
├── .env.example
├── .gitignore
├── package.json
├── package-lock.json
├── README.md
└── server.js
