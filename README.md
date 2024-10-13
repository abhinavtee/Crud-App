# Crud App

## Description
This is a CRUD (Create, Read, Update, Delete) application built with **Spring Boot** for the backend and **React** for the frontend. The application allows users to manage user data efficiently.

## Features
- **Create** a new user record
- **Read** existing user records
- **Update** user information
- **Delete** user records

## Technologies Used
- **Backend:** Spring Boot, Maven
- **Frontend:** React

## Installation Instructions

### Backend
1. Navigate to the `Backend/crud` directory:
   ```bash
   cd Backend/crud
   
**Install dependencies**
mvn install

**Run the Spring Boot application:**
mvn spring-boot:run

**Frontend**
Navigate to the Frontend/crudapp director
cd Frontend/crudapp
Install dependencies:
npm install
Start the React application:
npm start

**Usage**
Access the frontend application at http://localhost:3000 (default React port).
The backend API will be available at http://localhost:8080 (default Spring Boot port).

**API Endpoints**
GET /api/users: Retrieve a list of users.
POST /api/users: Create a new user.
PUT /api/users/:id: Update an existing user.
DELETE /api/users/:id: Delete a user

**Contributing**
Feel free to submit a pull request or open an issue if you would like to contribute to this project!

**License**
This project is licensed under the MIT License.
