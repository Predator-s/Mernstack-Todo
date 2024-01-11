# Todo App

This is a Todo App built with React.js for the frontend, Node.js and Express for the backend, and PostgreSQL for the database.

## Features

- User authentication with JWT token
- CRUD operations for categories
- CRUD operations for todos
- CRUD operations for subtodos associated with each todo
- Search functionality for todos
- Pagination support for todos
- Filtering todos by category

## Technologies Used

- React.js
- TailwindCSS
- Express.js
- Postgres SQL
- JSON Web Tokens (JWT)
- bcrypt for password hashing

## Project Structure

The project is organized into two main folders: `client` and `server`.

### Client

The `client` folder contains the React.js application built with Tailwind for styling.

#### Installation

```bash
cd client
npm install
```

#### Usage

```bash
npm start
```

### Server

The `server` folder contains the Node.js and Express backend, along with the PostgreSQL database.

#### Installation

1. Create a PostgreSQL database and update the connection details in `server/configs/db.js`.

2. Install dependencies:

```bash
cd server
npm install
```

3. Run the server:

```bash
npm start
```

## Endpoints

- `POST /register`: Register a new user
- `POST /login`: Login and obtain a JWT token
- `GET /categories`: Get all categories
- `POST /addCategory`: Add a new category
- `DELETE /deleteCategory/:id`: Delete a category by ID
- `GET /todos`: Get all todos with optional pagination, search, and category filter
- `POST /addTodo`: Add a new todo
- `DELETE /deleteTodo/:id`: Delete a todo by ID
- `PUT /toggleTodo/:id`: Toggle the completion status of a todo
- `GET /subtodos/:todoId`: Get all subtodos for a specific todo
- `POST /addSubTodo`: Add a new subtodo to a specific todo
- `DELETE /deleteSubTodo/:id`: Delete a subtodo by ID
- `PUT /toggleSubTodo/:id`: Toggle the completion status of a subtodo

## Screenshots
![Screenshot (18)](https://github.com/Predator-s/Mernstack-Todo/assets/123081811/7bfd2a86-84c9-49b5-b333-805f0f7e6a46)
![Screenshot (20)](https://github.com/Predator-s/Mernstack-Todo/assets/123081811/492423b9-a849-4293-8574-b25a91808671)
![Screenshot (21)](https://github.com/Predator-s/Mernstack-Todo/assets/123081811/406aabdc-6dfc-44cc-b09d-8ad0b05e004a)
![Screenshot (23)](https://github.com/Predator-s/Mernstack-Todo/assets/123081811/b31ada00-5f1f-4622-82bf-29c73197e21c)




