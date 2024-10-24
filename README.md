# Book Store Project

## Overview
The Book Store Project is a full-stack web application that allows users to create, read, update, and delete books. The application is built using a microservices architecture, with a separate backend and frontend.

## Project Structure
The project is divided into two main directories:
- `backend`: contains the server-side code, written in Node.js and Express.js
- `frontend`: contains the client-side code, written in React.js

## Backend
The backend is responsible for managing the data and providing APIs for the frontend to interact with. It uses the following technologies:
- Node.js: as the runtime environment
- Express.js: as the web framework
- Mongoose: as the ORM for interacting with the MongoDB database

### API Endpoints
- `GET /books`: retrieves a list of all books
- `GET /books/:id`: retrieves a single book by ID
- `POST /books`: creates a new book
- `PUT /books/:id`: updates a single book
- `DELETE /books/:id`: deletes a single book

## Frontend
The frontend is responsible for rendering the user interface and interacting with the backend APIs. It uses the following technologies:
- React.js: as the UI library
- React Router: for client-side routing
- Axios: for making HTTP requests to the backend

### Features
The frontend provides the following features:
- A list view of all books
- A detail view of a single book
- A form to create a new book
- A form to edit an existing book
- A button to delete a book

## Core Features
The application provides the following features:
- CRUD operations for books
- Validation for book fields
- Error handling for API requests

## Installation
To install the application, follow these steps:

1. Clone the repository:
```bash
git clone https://github.com/your-username/book-store-project.git
```

2. Install dependencies:
```bash
# Install backend dependencies
cd backend
npm install

# Install frontend dependencies
cd ../frontend
npm install
```

3. Start the backend server:
```bash
cd backend
npm start
```

4. Start the frontend server:
```bash
cd frontend
npm start
```

## Usage
To use the application, follow these steps:

1. Open a web browser and navigate to `http://localhost:3000`
2. Click on the "Books" tab to view the list of books
3. Click on a book title to view the book details
4. Click on the "Create Book" button to create a new book
5. Click on the "Edit Book" button to edit an existing book
6. Click on the "Delete Book" button to delete a book
