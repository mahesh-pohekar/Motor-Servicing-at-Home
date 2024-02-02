# Motor Servicing at Home

Motor Servicing at Home is a web application built with Node.js, Express, and React for managing service requests between service providers and requestors.

## Features

- **User Authentication**: Allows users to sign up, log in, and log out.
- **Service Requests**: Create, view, and manage service requests.
- **Location-based Services**: Find and connect with nearby service providers.

## Prerequisites

- Node.js: [Download Node.js](https://nodejs.org/)
- npm: Included with Node.js installation
- MySQL: [Download MySQL](https://www.mysql.com/)

## Backend

### Getting Started

1. Navigate to the backend directory:

   ```bash
   cd backend
2.	Install dependencies:
    ```bash
  	npm install 
3. Set up the database:
    •	Create a MySQL database.
    •	Update the database configuration in config/db.js.
5.	Run the backend application:
    ```bash
    npm start 
The backend will be available at http://localhost:3001.

### Configuration
•	Database configuration: Update config/db.js with your MySQL database details.
•	Session secret: Set a secure secret key in routes/authRoutes.js and server.js.


## Frontend

### Getting Started
1.	Navigate to the frontend directory:
    ```bash
    cd frontend 
2.	Install dependencies:
    ```bash
    npm install 
3.	Run the frontend application:
    ```bash
    npm start 
The frontend will be available at http://localhost:3000.

