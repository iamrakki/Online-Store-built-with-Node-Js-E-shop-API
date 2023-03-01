# NodeJs: Build The Complete E-Commerce Web API

This project is a complete e-commerce web API built using NodeJS. The API allows for the creation, reading, updating, and deleting of resources such as products, orders, and customers. The API is also designed to be secure and scalable, allowing for easy integration with other applications.

# Run

### Install

```
npm install
```

### Start API

```
npm start
```

# Routes

### Products

```
GET      /api/v1/products
GET      /api/v1/products/:id
POST     /api/v1/products
PUT      /api/v1/products/:id
DELETE   /api/v1/products/:id
PUT gallery-images : /api/v1/products/gallery-images/:id
GET featured products: /api/v1/products/get/featured/:count
GET products count: /api/v1/products/get/count
```

### Orders

```
GET      /api/v1/orders
GET      /api/v1/orders/:id
POST     /api/v1/orders
PUT      /api/v1/orders/:id
DELETE   /api/v1/orders/:id
GET orders count: /api/v1/orders/get/count
```

### Users

```
GET      /api/v1/users
GET      /api/v1/users/:id
POST     /api/v1/users
PUT      /api/v1/users/:id
DELETE   /api/v1/users/:id
GET users count: /api/v1/users/get/count
```

#### Register new user

```
POST     /api/v1/users/register
```

#### Login user

To login the user and get the auth token you can use:

```
POST     /api/v1/users/login
```

# Database Integration
This project uses MongoDB as its database. To integrate the database into the project, the Mongoose library is used to create models and interact with the database.

# Authentication and Authorization
This project uses JSON Web Tokens (JWT) to authenticate and authorize users. The API includes endpoints for user login and registration, as well as routes that require authentication and authorization to access.

# Payment Integration
This project integrates with the Stripe payment gateway to allow for secure and convenient payment processing.

# Testing and Deployment
Testing for this project is done using the Jest testing framework. The API is deployed to a production environment using Docker and Kubernetes for containerization and orchestration.




