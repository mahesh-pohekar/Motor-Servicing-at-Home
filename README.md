# Motor Servicing at Home

Motor Servicing at Home is a web application built with Node.js, Express, and React for managing service requests between service providers and requestors.
## Customer UI
![image](https://github.com/mahesh-pohekar/Motor-Servicing-at-Home/assets/106031907/acf5faeb-1849-496c-bda6-1578c741ca0b)

![image](https://github.com/mahesh-pohekar/Motor-Servicing-at-Home/assets/106031907/74402489-4087-4069-bb03-f6cbd85254be)

![image](https://github.com/mahesh-pohekar/Motor-Servicing-at-Home/assets/106031907/637a8aae-b899-4b42-a341-c000d2c8f378)


## Admin UI
![image](https://github.com/mahesh-pohekar/Motor-Servicing-at-Home/assets/106031907/21d4ce22-e69c-40a9-9e56-67316af0a595)

![image](https://github.com/mahesh-pohekar/Motor-Servicing-at-Home/assets/106031907/dff01cab-1a57-4416-991e-89abb08f76b0)

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

