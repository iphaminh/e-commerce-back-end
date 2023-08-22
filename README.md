# E-commerce Back End Starter Code

An API for managing products, categories, and tags for an e-commerce platform.

## Table of Contents
Description
Installation
Usage
API Endpoints
Testing
Contributing
License
Contact
Description
This backend API allows users to manage products, categories, and tags for an e-commerce platform. Built with Node.js, Express.js, and Sequelize, it provides a robust set of endpoints for CRUD operations.

## Installation

Clone the repository:

git clone [https://github.com/iphaminh/e-commerce-back-end]

Navigate to the project directory:

cd [project_directory]

Install the required dependencies:

npm install

Set up your database and modify the config/connection.js file with your database credentials.
Run the database migrations:

npm run migrate

## Usage

To start the server, run:

npm start

## API Endpoints

Products

GET /api/products: Fetch all products.
GET /api/products/:id: Fetch a single product by ID.
POST /api/products: Add a new product.
PUT /api/products/:id: Update a product by ID.
DELETE /api/products/:id: Delete a product by ID.

Categories (Similarly)

Tags (Similarly)

## Walkthrough Video

https://drive.google.com/file/d/1nh8vEWX8rThPGrsXZg57zHcuLLxOFlO4/view

## Github Link

https://github.com/iphaminh/e-commerce-back-end

## Testing

(Provide information on how to run tests for your API, if applicable.)

## Contributing

Contributions are welcome! Please read the contributing guidelines first.

## License

This project is licensed under the MIT License. See the LICENSE file for details.