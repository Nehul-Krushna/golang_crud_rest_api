# Go REST API with Gorilla Mux and MySQL

This is a simple RESTful API written in Go that uses the Gorilla Mux router and MySQL database to perform CRUD operations on a collection of products.

## Installation

1. **Clone the repository:**
    ```bash
    https://github.com/Nehul-Krushna/golang_crud_rest_api.git
    cd golang_crud_rest_api
    ```

2. **Install dependencies:**
    ```bash
    go mod tidy
    ```

3. **Set up MySQL:**
    - Make sure you have MySQL installed and running on your system.
    - Create a MySQL database and adjust the connection string in `main.go` accordingly.

4. **Run the application:**
    ```bash
    go run main.go
    ```

## Usage

- **GET `/products`**: Get all products.
- **GET `/products/{id}`**: Get a specific product by ID.
- **POST `/products`**: Create a new product.
- **PUT `/products/{id}`**: Update an existing product.
- **DELETE `/products/{id}`**: Delete a product.

## Sample Product JSON

```json
{
    "id": 1,
    "code": "P123",
    "price": 100
}
