# Thread Clone

A thread clone application built using Node.js for the backend and React for the frontend. This project replicates the functionality of a thread-based discussion platform.

**Hosted Link:**

## Table of Contents

- [Overview]
- [Features]
- [Technologies Used]
- [Installation]
- [Configuration]
- [Running the Project]
- [API Endpoints]
- [Frontend]
- [License]

## Overview

This application is designed to mimic a thread-based discussion platform where users can create, view, and participate in threads. The backend is built with Node.js and Express, while the frontend is created using React.

## Features

- User authentication (login and signup)
- User profile management
- File upload functionality using Cloudinary
- Creating, viewing, and managing threads(POSTS)
- Posting and managing messages within threads
- Real-time messaging using [Socket.io](http://socket.io/)

## Technologies Used

- **Backend:**
    - Node.js
    - Express
    - jsonwebtoken
    - MongoDB
    - [Socket.io](http://socket.io/)
    - Cloudinary
    - bcryptjs
    - dotenv
    - cors
    - cookie-parser
- **Frontend:**
    - React
    - React Router
    - Socket.io-client

## Installation

1. **Clone the repository:**
    
    ```bash
    git clone <repository-url>
    cd <repository-directory>
    
    ```
    
2. **Start the backend server:**
    
    ```bash
    cd backend
    npm run dev
    
    ```
    
3. **Start the frontend server:**
    
    ```bash
    cd frontend
    npm run dev
    
    ```
    

## API Endpoints

### User Authentication:

- **POST /api/users/signup** - Sign up a new user
- **POST /api/users/login** - Log in a user

### Threads:

- **GET /api/feed** - Get all threads
- **POST /api/posts/create** - Create a new thread
- **GET /api/user/posts/:id** - Get a specific thread

### Messages:

- **POST /api/messages** - Post a new message
- **GET /api/messages/:Id** - Get messages for a specific thread