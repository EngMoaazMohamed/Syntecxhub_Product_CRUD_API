# Product CRUD API

A RESTful Product CRUD API built with Node.js, Express.js, MongoDB Atlas, and Mongoose.

## Features

- Create Product
- Get All Products
- Get Product By ID
- Update Product
- Delete Product
- Category Filtering
- Price Range Filtering
- Pagination
- Error Handling

## Technologies Used

- Node.js
- Express.js
- MongoDB Atlas
- Mongoose
- Postman

## API Endpoints

### Create Product

```http
POST /api/products
```

### Get All Products

```http
GET /api/products
```

### Get Product By ID

```http
GET /api/products/:id
```

### Update Product

```http
PUT /api/products/:id
```

### Delete Product

```http
DELETE /api/products/:id
```

### Filtering

```http
GET /api/products?category=Electronics
```

### Price Range

```http
GET /api/products?minPrice=100&maxPrice=1000
```

### Pagination

```http
GET /api/products?page=1&limit=5
```

## Author

**Moaaz Mohamed**

Computer Engineering Student
