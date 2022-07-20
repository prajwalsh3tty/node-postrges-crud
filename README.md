# Node.js PostgreSQL CRUD

The following table shows overview of the Rest APIs that will be exported:

- GET `api/products` get all products
- GET `api/products/:id` get Product by id
- POST `api/products` add new Product
- PUT `api/products/:id` update Product by id
- DELETE `api/products/:id` remove Product by id
- DELETE `api/products` remove all products
- GET `api/products/published` find all published products
- GET `api/products?title=[laptop]` find all products which title contains 'laptop'

## Project setup

```
npm install
```

### Run

```
node server.js
```
