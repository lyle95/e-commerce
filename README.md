## Run Locally

Clone the project

```bash
  git clone https://ecommerce-assignment-admin@bitbucket.org/ecommerce-assignment/ecommerce.git
```

Go to the project directory

```bash
  cd ecommerce
```

Install dependencies

```bash
  npm install

  or 

  npm install react-material-ui-carousel --save --legacy-peer-deps
```

Start the server

```bash
  npm start
```

The server should now be running. You can access the application by opening a web browser and entering the following URL:

```bash
  http://localhost:3000
```

# E-Commerce Product API

## Tech Stack
Backend: Node.js, Express
Database: MongoDB(local)

## Run the server
node server.js

## sample curl
### Return all products
curl http://localhost:4000/api/v1/products
### Filter products by category
curl "http://localhost:4000/api/v1/products?category=Apparel"