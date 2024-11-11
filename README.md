# MERN Todo Application

A simple Todo application built with the MERN stack (MongoDB, Express.js, React, and Node.js).

## Features

- Create new todos
- View list of todos
- Delete existing todos
- Real-time updates
- MongoDB data persistence
- Clean and responsive UI

## Technologies Used

- **Frontend**:
  - React.js
  - Axios for HTTP requests
  - CSS for styling

- **Backend**:
  - Node.js
  - Express.js
  - MongoDB (local installation)
  - Mongoose for database modeling

## Prerequisites

Before running this application, make sure you have the following installed:
- Node.js (v12 or higher)
- MongoDB (local installation)
- npm (Node Package Manager)

## Installation and Setup

### Backend Setup

1. Navigate to backend directory:
```bash
cd backend
```

2. Install dependencies:
```bash
npm install
```

3. Start the server:
```bash
npm start
```

The backend server will run on port 5000.

### Frontend Setup

1. Navigate to frontend directory:
```bash
cd frontend
```

2. Install dependencies:
```bash
npm install
```

3. Start the application:
```bash
npm start
```

The frontend application will run on port 3000.

## Project Structure

```
mern-todo-app/
├── backend/
│   ├── node_modules/
│   ├── server.js
│   └── package.json
└── frontend/
    ├── node_modules/
    ├── public/
    ├── src/
    │   ├── App.js
    │   ├── App.css
    │   └── index.js
    └── package.json
```

## API Endpoints

- `GET /todos` - Get all todos
- `POST /todos` - Create a new todo
- `DELETE /todos/:id` - Delete a todo by ID

## Usage

1. Start MongoDB service on your machine
2. Run the backend server
3. Run the frontend application
4. Access the application at `http://localhost:3000`

## Author

- **Sushma**
  - GitHub: [@sushma5065](https://github.com/sushma5065)
