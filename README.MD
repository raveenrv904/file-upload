````markdown
# File Upload Starter

This repository provides a simple file upload starter using Node.js, Express, MongoDB, and Cloudinary.

## Features

- Create and retrieve products with image uploads
- Local and Cloudinary storage options for product images

## Getting Started

### Prerequisites

- Node.js installed
- MongoDB Atlas account (or local MongoDB server)
- Cloudinary account

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/your-repository.git
   ```
````

2. Install dependencies:

   ```bash
   cd your-repository
   npm install
   ```

3. Create a `.env` file in the root directory and add the following environment variables:

   ```env
   PORT=5000
   MONGO_URI=your-mongodb-uri
   CLOUD_NAME=your-cloudinary-cloud-name
   CLOUD_API_KEY=your-cloudinary-api-key
   CLOUD_API_SECRET=your-cloudinary-api-secret
   ```

### Usage

1. Run the application:

   ```bash
   npm start
   ```

2. Visit [http://localhost:5000](http://localhost:5000) to access the File Upload Starter.

## API Endpoints

- **Create Product:** `POST /api/v1/products`
- **Get All Products:** `GET /api/v1/products`
- **Upload Product Image:** `POST /api/v1/products/uploads`

## Structure

- **Controllers:**

  - `productController.js`: CRUD operations for products
  - `uploadsController.js`: Image upload methods

- **Routes:**

  - `productRoutes.js`: Defines product-related routes

- **Middleware:**

  - `not-found.js`: 404 error handler
  - `error-handler.js`: Global error handler

- **Other Files:**
  - `app.js`: Express application setup
  - `db/connect.js`: MongoDB connection setup
  - `public/`: Static files directory
  - `models/Product.js`: Product model definition

## Contributing

Contributions are welcome! Please follow the [Contribution Guidelines](CONTRIBUTING.md).

## License

This project is licensed under the [MIT License](LICENSE).

```

```
