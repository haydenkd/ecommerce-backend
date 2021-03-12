# ecommerce-backend

## Description

A backend for an ecommerce website that allows for inventory management and organization.

## Installation

1. Clone the GitHub repo and install dependencies. Note: You will need Node.js for this project.
Run `npm install` in the terminal within the root directory to install the necessary assets.

2. Create a .env file in the root of the project that contains your SQL username and password in the following format:
```
DB_NAME='ecommerce_db
DB_USER='YOUR_USERNAME'
DB_PW='YOUR_PASSWORD'
```

3. Create and seed the database. The database should be named `ecommerce_db` and should be sourced from `db/schema.sql.` To seed the database, run the command `npm run seed` from the root directory in your terminal.

## Usage

To start the server, simply run the command `npm start` and make HTTP requests to the localhost server using your own program of choice. The default port is 3001.

For making POST or PUT requests, check the seed data for proper JSON formatting.