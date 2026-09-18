# Event Management API (Task 2)

Backend RESTful API built with Node.js, Express, MongoDB, and JWT Authentication.

## Features
- User Authentication (Register, Login, JWT Token)
- Protected Routes using Auth Middleware
- Event CRUD Operations (Create, Read, Update, Delete)
- Password Hashing with Bcrypt
- MongoDB Database Storage

## Tech Stack
- **Node.js** & **Express.js**
- **MongoDB** & **Mongoose**
- **JWT** (JSON Web Tokens) & **bcryptjs**

## API Endpoints

### Auth Routes
- `POST /auth/register` - Register a new user
- `POST /auth/login` - Login user & receive JWT token

### Event Routes
- `GET /events` - Get all events (Public)
- `GET /events/:id` - Get event by ID (Public)
- `POST /events` - Create event (Protected - JWT Required)
- `PUT /events/:id` - Update event (Protected - JWT Required)
- `DELETE /events/:id` - Delete event (Protected - JWT Required)

## Setup & Running Locally
1. Clone the repository
2. Run `npm install`
3. Create `.env` file with `PORT`, `MONGO_URI`, and `JWT_SECRET`
4. Start server using `node server.js`
5.
