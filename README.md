# 🔑 Secure User Authentication with MERN Stack

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://github.com/abdussameea1813/authentication_mern/graphs/commit-activity)
[![Open Source Love](https://badges.frapsoft.com/os/v1/open-source.svg?v=103)](https://github.com/abdussameea1813/authentication_mern)

**This repository contains a robust and secure user authentication system built using the MERN stack (MongoDB, Express.js, React, Node.js).** It provides a solid foundation for implementing user registration, login, and protected routes in your web applications.

## ✨ Key Features

* **Secure Password Handling:** Utilizes `bcrypt` for password hashing, ensuring user credentials are never stored in plain text.
* **JSON Web Tokens (JWT):** Implements JWT for secure session management and authorization. Once logged in, users receive a token that is used to access protected routes.
* **User Registration:** Allows new users to create accounts with email and password.
* **User Login:** Enables existing users to securely log in to the application.
* **Protected Routes:** Demonstrates how to protect specific routes so only authenticated users can access them.
* **Clear Code Structure:** Well-organized code with comments to facilitate understanding and modification.
* **Basic Error Handling:** Includes basic error handling for common authentication scenarios.
* **Modular Design:** Separates frontend and backend logic for better maintainability.

## 🛠️ Tech Stack

* **Frontend:**
    * [React](https://react.dev/) - A JavaScript library for building user interfaces.
    * [Axios](https://axios-http.com/docs/intro) - Promise-based HTTP client for making API requests.
    * [React Router](https://reactrouter.com/en/main) - For handling client-side routing.
* **Backend:**
    * [Node.js](https://nodejs.org/en/) - JavaScript runtime environment.
    * [Express.js](https://expressjs.com/) - Minimalist and flexible Node.js web application framework.
    * [MongoDB](https://www.mongodb.com/) - NoSQL database for storing user data.
    * [Mongoose](https://mongoosejs.com/) - Elegant MongoDB object modeling for Node.js.
    * [bcrypt](https://www.npmjs.com/package/bcrypt) - For password hashing.
    * [jsonwebtoken](https://jwt.io/) - For creating and verifying JWTs.
    * [dotenv](https://www.npmjs.com/package/dotenv) - To load environment variables from a `.env` file.
    * [CORS](https://expressjs.com/en/resources/middleware/cors.html) - Middleware to enable Cross-Origin Resource Sharing.

## 🚀 Getting Started

Follow these steps to get a local copy up and running:

### Prerequisites

* [Node.js](https://nodejs.org/en/) (version 18 or higher recommended)
* [npm](https://www.npmjs.com/) (usually comes with Node.js) or [yarn](https://yarnpkg.com/)
* [MongoDB](https://www.mongodb.com/try/download/community) - Ensure MongoDB is installed and running on your system.

### Installation

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/abdussameea1813/authentication_mern.git](https://github.com/abdussameea1813/authentication_mern.git)
    cd authentication_mern
    ```

2.  **Install backend dependencies:**
    ```bash
    cd backend
    npm install
    # or
    yarn install
    ```

3.  **Install frontend dependencies:**
    ```bash
    cd ../frontend
    npm install
    # or
    yarn install
    ```

4.  **Configure environment variables:**
    * Create a `.env` file in the `backend` directory.
    * Add the following environment variables (replace with your actual values):
        ```env
        PORT=5000
        MONGO_URI=your_mongodb_connection_string
        JWT_SECRET=your_secret_jwt_key
        ```

5.  **Run the backend server:**
    ```bash
    cd ../backend
    npm run dev
    # or
    yarn dev
    ```
    The backend server should start on port 5000 (or the port you specified in `.env`).

6.  **Run the frontend development server:**
    ```bash
    cd ../frontend
    npm start
    # or
    yarn start
    ```
    The frontend application should open in your browser (usually on `http://localhost:3000`).

## 📂 Project Structure﻿# authentication_mern
