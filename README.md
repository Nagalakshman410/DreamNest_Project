# DreamNest_Project

## <a name="table">Table of Contents</a>

1. [Introduction](#introduction)
2. [Motivation](#motivation)
3. [Tech Stack](#tech-stack)
4. [Features](#features)
5. [Quick Start](#quick-start)

## Introduction

DreamNest is a full-stack web application for booking and hosting vacation rentals, inspired by platforms like Airbnb. Users can register, log in, browse listings, create new property listings, manage bookings, and maintain wish lists.

## Motivation

The motivation behind DreamNest is to provide a seamless and user-friendly platform for both travelers and hosts. It aims to simplify the process of finding unique accommodations and managing rental properties, making travel planning and property management more accessible.

## Tech Stack

**Frontend:**
- React
- Redux Toolkit & Redux Persist
- React Router
- SCSS (Sass)
- Material UI & React Icons

**Backend:**
- Node.js
- Express.js
- MongoDB (Mongoose)
- Multer (for file uploads)
- JWT (JSON Web Tokens) for authentication
- bcryptjs for password hashing

## Features

- User registration and authentication (with profile image upload)
- Browse listings by category, search or all properties
- Create, edit and manage property listings (with photo uploads)
- Add/remove properties to/from wish lists
- Book properties and manage trip reservations
- View and manage your own properties and reservations
- Responsive design for desktop and mobile

## Quick Start

### Prerequisites

- Node.js and npm installed
- MongoDB instance (local or cloud, e.g., MongoDB Atlas)

**Cloning the Repository**

```bash
git clone https://github.com/Nagalakshman410/Portfolio.git
```

### Backend

1. Navigate to the `server` directory:
   ```bash
   cd server
   ```

2. Install dependencies:
    ```bash
    npm install
    ```

3. Create a .env file in the server directory with the following variables:
    ```env
    MONGO_URL=your_mongodb_connection_string
    JWT_SECRET=your_jwt_secret
    PORT=3001
    ```

4. Start the backend serve:
    ```bash
    npm start
    ```

### Frontend

1. Open a new terminal and navigate to the client directory:
    ```bash
    cd client
    ```

2. nstall dependencies:
    ```bash
    npm install
    ```

3. Start the frontend development server:
    ```bash
    npm start
    ```

4. Open http://localhost:3000 in your browser to view the project.
