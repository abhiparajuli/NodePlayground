# Node Farm

This Node Farm project is a Node.js application that serves a simple website displaying product information. The project structure includes HTML templates, JSON data, and JavaScript files for server logic. This is a project based on Jonas Schmedman's tutorials.

## Key Components

### HTML Templates
- `template-overview.html`: Displays an overview of all products.
- `template-card.html`: Represents individual product cards.
- `template-product.html`: Displays detailed information about a single product.

### JSON Data
- `data.json`: Contains product information such as name, image, origin, nutrients, quantity, price, and description.

### JavaScript Files
- `index.js`: Main server file that reads templates and data, creates an HTTP server, and handles routing for different pages (overview, product, API).
- `replaceTemplate.js`: Module that replaces placeholders in HTML templates with actual product data.

### Server Logic
- Reads HTML templates and JSON data.
- Uses the `slugify` library to create URL-friendly slugs for product names.
- Handles routing for:
  - Overview page (`/overview`): Displays all products.
  - Product page (`/product`): Displays detailed information for a specific product.
  - API endpoint (`/api`): Serves product data in JSON format.
  - 404 Not Found page for invalid routes.

### Dependencies
- `slugify`: Used to create URL-friendly slugs.
- `nodemon`: Development dependency for automatically restarting the server on file changes.

## How to Run

1. Install dependencies:
   ```sh
   npm install
2. Run the server:
   ```sh
   npm start
3. Open your browser and navigate to http://127.0.0.1:8000 to view the application.
   
