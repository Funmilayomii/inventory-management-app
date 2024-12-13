# Products Collection API

A simple API server built with Node.js (without frameworks) to manage inventory information. The server uses the file system to persist data (`items.json`). This API allows you to perform CRUD operations on a collection of items, including adding, retrieving, updating, and deleting items entries.



## Features

- **Create an Item**: Add new items.
- **Get All Items**: Retrieve a list of all items.
- **Get One Item**: Retrieve details of a specific item by its ID.
- **Update an Item**: Modify an existing item's attributes.
- **Delete an Item**: Remove an item from the collection.

## Item Structure

Each item has the following attributes:
- `id` (string): A unique identifier for the item.
- `name` (string): The name of the item.
- `price` (number): The price of the item.
- `size` (string): The size of the item (`small`, `medium`, or `large`).

## Installation

1. Clone the repository or download the code:

   git clone <repository_url>
   
2. Navigate to the project directory:

   cd book-collection-api

3. Install dependencies:

   npm install

4. Start the server:

   npm start

The API will run on http://localhost:5001 by default.


## Technologies Used

- **Node.js**: Runtime environment for Javascript
- **JSON**: Data format for API requests and responses 