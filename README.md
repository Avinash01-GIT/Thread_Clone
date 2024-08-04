# Thread Clone

A thread clone application built using Node.js for the backend and React for the frontend. This project replicates the functionality of a thread-based discussion platform.

**Hosted Link:** https://thread-clone-i33s.onrender.com

## Table of Contents

- [Overview]
- [Features]
- [Technologies Used]
- [Installation]
- [Configuration]
- [Running the Project]
- [API Endpoints]
- [Frontend]

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

![image](https://github.com/Avinash01-GIT/Thread_Clone/blob/main/ThreadSS/Tsignup.png)
![image](https://github.com/Avinash01-GIT/Thread_Clone/blob/main/ThreadSS/Tlogin.png)
![image](https://github.com/Avinash01-GIT/Thread_Clone/blob/main/ThreadSS/Tfeed.png)
![image](https://github.com/Avinash01-GIT/Thread_Clone/blob/main/ThreadSS/TChat.png)

## Usage
Ensure you have MongoDB installed and running. Modify the .env file with your specific configurations before starting the server. Use tools like Postman or curl to interact with the API endpoints.

## Contributing
Contributions are welcome! If you'd like to contribute to this project, please follow these guidelines:

Fork the repository and create a new branch.
Make your changes and test thoroughly.
Submit a pull request detailing the changes and improvements made.
