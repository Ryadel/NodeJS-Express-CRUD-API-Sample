# NodeJS Express CRUD API Sample

A simple and effective CRUD API built using Node.js and Express. This project serves as a lightweight boilerplate for developers who want to create RESTful Web APIs with basic CRUD functionalities (Create, Read, Update, Delete) in Node.js using the Express framework.

## Features

- Lightweight and minimal setup
- Built entirely with Node.js and Express
- In-memory data storage (no external database required)
- Full CRUD endpoints:
  - `GET /api/items` – Retrieve all items
  - `GET /api/items/:id` – Retrieve an item by ID
  - `POST /api/items` – Create a new item
  - `PUT /api/items/:id` – Update an existing item
  - `DELETE /api/items/:id` – Delete an item

## Requirements

- [Node.js](https://nodejs.org/) v14 or higher
- [npm](https://www.npmjs.com/) (Node package manager)

## Getting Started

1. Clone this repository or [download the ZIP](https://github.com/Ryadel/NodeJS-Express-CRUD-API-Sample/archive/refs/heads/main.zip).

2. Navigate to the project folder:

```bash
cd NodeJS-Express-CRUD-API-Sample
```

3. Install dependencies:

```bash
npm install
```

4. Start the server:

```bash
npm start
```

The API server will be running at:

```
http://localhost:3000
```

## Example Endpoints

You can test the API using tools like [Postman](https://www.postman.com/) or [curl](https://curl.se/).

### Create an Item
```http
POST /api/items
Content-Type: application/json

{
  "name": "My New Item"
}
```

### Get All Items
```http
GET /api/items
```

### Get a Specific Item
```http
GET /api/items/1
```

### Update an Item
```http
PUT /api/items/1
Content-Type: application/json

{
  "name": "Updated Item"
}
```

### Delete an Item
```http
DELETE /api/items/1
```

## Notes

- This project uses an in-memory JavaScript array to store data. All items are lost when the server restarts.
- The code is fully self-contained and meant for educational purposes, prototyping, and quick tests.
- No database is required or configured.

## Further Reading

For a detailed explanation and walkthrough of the code, please refer to the original article published on Ryadel.com:

- 📖 [Node.js and Express CRUD API Code Sample – Boilerplate and Code Explained](https://www.ryadel.com/en/node-js-express-crud-api-in-node-js-and-express-code-sample-boilerplate/)

## 📄 License

This project is open-source and available under the MIT License.
