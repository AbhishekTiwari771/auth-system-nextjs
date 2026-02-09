# Full Stack Authentication System

This project is a full-stack user authentication system built as part of a technical assignment.

## Tech Stack

Frontend:
- Next.js (App Router)
- TypeScript
- Tailwind CSS
- Axios

Backend:
- Node.js
- Express.js
- MongoDB Atlas
- Mongoose
- JWT Authentication
- bcrypt (password hashing)

## Features

- User Registration (Name, Email, Password)
- Password hashing using bcrypt
- User Login with JWT authentication
- Token stored in HTTP-only cookies
- Protected Dashboard route
- Logout functionality
- MongoDB database integration
- Clean folder structure (controllers, routes, middleware, models)

## Project Structure

auth-assignment/
client/ → Next.js frontend
server/ → Express backend


## Setup Instructions

### 1. Clone the repository

```bash
git clone https://github.com/AbhishekTiwari771/auth-system-nextjs.git
cd auth-system-nextjs
```

## Backend Seup
cd server
npm install

## Create .env file inside /server
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key

npm run dev

http://localhost:5000


## Frontend Setup
cd client
npm install
npm run dev

http://localhost:3000

