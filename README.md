# E-Commerce Backend

This project is a backend application for an e-commerce site. Built using Node.js, Express, Sequelize, and MySQL, it provides API endpoints to manage a database of products, categories, tags, and product-tag associations.

## Features

- **Product Management**: Create, read, update, and delete products.
- **Category Management**: Organize products into categories.
- **Tag Management**: Assign tags to products for easy searching.
- **Product-Tag Association**: Link products with tags and manage their relationships.

## Installation

1. Clone the repository to your local machine.
2. Install the required npm packages by running
   ```bash npm install ```
4. Configure your database settings in `connection.js`.
5. Initialize the database by running the schema from `schema.sql`.
6. Seed the database with test data by running
   ```bash npm run seed ```
8. Start the server with `npm start`.

## API Endpoints

The application exposes the following endpoints:

- `/api/products`: CRUD operations for products.
- `/api/categories`: CRUD operations for categories.
- `/api/tags`: CRUD operations for tags.
- `/api/product-tags`: Manage associations between products and tags.

## Models

- `Product`: Represents products being sold.
- `Category`: Represents categories for products.
- `Tag`: Represents descriptive tags for products.
- `ProductTag`: Represents many-to-many associations between products and tags.

## Seeding the Database

The project includes seed files to populate the database with initial data:

- `category-seeds.js`
- `product-seeds.js`
- `tag-seeds.js`
- `product-tag-seeds.js`

Run `npm run seed` to seed your database.

## Technologies Used

- Node.js
- Express.js
- Sequelize ORM
- MySQL

## Contributing

Contributions are welcome. Please open an issue to discuss proposed changes or open a Pull Request.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more information.

## Questions

If you have any questions or comments about the repo, open an issue or contact me directly at [binitakhua@gmail.com](mailto:binitakhua@gmail.com).
