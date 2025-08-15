[README.md](https://github.com/user-attachments/files/21798590/README.md)
# Todo List App with User Authentication

This is a simple **MERN** (MongoDB, Express, React, Node.js) Todo app where each user can sign up, log in, and manage their own tasks.  
It uses **JWT** for authentication and **bcrypt** for password hashing.

## Features
- User **Sign Up** and **Login**
- **JWT-based authentication** (secure)
- Add, edit, delete, and mark tasks as complete
- Each user sees only their own tasks
- **Light/Dark theme toggle** (default is white)
- Styled with plain CSS (no Tailwind)

## Tools Used
- **MongoDB** – stores users and tasks
- **Express.js** – backend API
- **React.js** – frontend UI
- **Node.js** – server runtime
- **JWT** – authentication tokens
- **bcrypt** – password hashing

## How to Run

### 1. Backend (Server)

cd server

npm install

npm run dev

### 2. Frontend (Client)
Open a new terminal:

cd client

npm install

npm run dev


Frontend runs at **http://localhost:5173**  
Backend runs at **http://localhost:5000**

## Process of Making This Project
1. Set up **backend** with Express and MongoDB.
2. Created **user model** and used **bcrypt** to hash passwords.
3. Added **JWT authentication** for login and protected routes.
4. Built **task routes** so users can add, edit, delete, and view only their own tasks.
5. Made the **frontend** with React (login, signup, dashboard, task CRUD).
