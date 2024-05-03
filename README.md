# newbackend_pritee

Description
This is a RESTful API for managing books. It provides endpoints for performing CRUD operations on book data, including adding new books, retrieving book details, updating book information, and deleting books.

Technologies Used

- Express.js: A web application framework for Node.js, used for building APIs and web applications.
- MongoDB: A NoSQL database used for storing book data.
- CORS: Middleware for enabling Cross-Origin Resource Sharing (CORS) in Express.js.
- Body-parser: Middleware for parsing incoming request bodies in Express.js.

Installation
Clone the repository:
git clone https://github.com/priteetangle1984/newbackend_pritee.git

Navigate to the project directory:
cd backend_new

Install dependencies:
npm install

Set up the MongoDB database:

- Install MongoDB locally or use a cloud-hosted MongoDB service.
- Update the MongoDB connection URI in the config/db.js file.

Start the server:
npm start

The API will be accessible at http://localhost:8082.

API Endpoints

- GET /api/books: Retrieve all books.
- GET /api/books/:id: Retrieve a specific book by its ID.
- POST /api/books: Add a new book.
- PUT /api/books/:id: Update an existing book by its ID.
- DELETE /api/books/:id: Delete a book by its ID

Usage

- Use tools like Postman or curl to make HTTP requests to the API endpoints.
- Send GET, POST, PUT, or DELETE requests to perform CRUD operations on book data.
