# Product API

This is a simple RESTful API for managing products, built with Node.js and Express. It supports operations to get all products, get a single product by ID, add a new product, update an existing product, and delete a product.

## Getting Started

### Prerequisites

- Node.js (v12.x or later)
- npm (v6.x or later)

### Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/HumairaBashir/Task-2-Backend-RestFul-API.git
    cd Task-2-Backend-RestFul-API
    ```

2. Install the dependencies:
    ```sh
    npm install
    ```

### Running the API  

Start the server:
```sh
node server.js

### Test APIS in PostMan


### 1.  To get All Products run this API in postmam with method GET
http://localhost:3000/products


### 2. To get a single Product by ID run this API in postman with method GET 

//last parameter is product ID which can me change with any other product ID

http://localhost:3000/products/6157e32c-c89f-44f3-abdb-388581f6833b


### 3. To add a new Product run this API in postman with method POST and in body add the data as JSON 

{
  "name": "Product 3",
  "price": 30.99,
  "description": "Description of Product 3"
}

http://localhost:3000/products


### 4. To Update the Existing Product use this API in postman with method PUT with that specific Product ID , in body add the data as JSON

{
  "name": "Updated Product 1",
  "price": 15.99,
  "description": "Updated description of Product 1"
}


http://localhost:3000/products/6157e32c-c89f-44f3-abdb-388581f6833b


### 5. To delete a specific Product use this API in postman with method DELETE with that specific Product ID 

http://localhost:3000/products/6157e32c-c89f-44f3-abdb-388581f6833b
