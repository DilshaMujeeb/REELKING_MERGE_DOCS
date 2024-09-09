# ReelKing Project Documentation

This repository contains documentation and link to the code for the project "ReelKing". 

## Overview

ReelKing is a comprehensive social media web application designed to facilitate various interactions among users, including chatting, 
following/unfollowing, liking, commenting, sharing posts, and updating profile pictures. The primary objective of ReelKing is to provide 
a dynamic and engaging platform for users to connect, communicate, and share content within a social network environment.

## Frontend Repository

- Link to the frontend repository: [Frontend Repository](https://github.com/DilshaMujeeb/Social_Media_Client)
The frontend of ReelKing leverages a modern stack of technologies to deliver a seamless user experience:

React: Utilized as the core framework for building the user interface,
React enables the creation of dynamic and interactive components.

Redux: Employed for state management, Redux ensures a predictable state 
container for the application, facilitating efficient data flow and manipulation.

JWT (JSON Web Tokens): Implemented for user authentication and authorization, 
JWT provides a secure and stateless mechanism for transmitting user identity information between the frontend and backend.

Axios: Utilized as the HTTP client for making asynchronous requests to the backend server,
Axios simplifies the process of handling AJAX requests and responses.

Cloudinary: Integrated for cloud-based image and video management, 
Cloudinary enables efficient storage, optimization, and delivery of media assets within the application.

CSS: Used for styling and layout design, 
CSS is employed to enhance the visual presentation of components and ensure a consistent user interface across different devices and screen sizes.

## Backend Repository

- Link to the backend repository: [Backend Repository](https://github.com/DilshaMujeeb/Social_Media_server)
-The backend of ReelKing is powered by a robust stack of technologies,
providing the foundation for secure and efficient server-side operations:

Node.js: Employed as the runtime environment, 
Node.js enables the execution of JavaScript code on the server-side, facilitating non-blocking, 
event-driven architecture for scalable backend applications.

MongoDB: Utilized as the database management system, 
MongoDB offers a flexible and scalable NoSQL solution for storing and managing application data, 
providing support for complex data structures and high-volume transactions.

Express: Leveraged as the web application framework for Node.js, 
Express simplifies the process of building robust and modular backend APIs, 
offering a wide range of features for routing, middleware integration, and request handling.

RESTful API: Implemented to facilitate communication between the frontend and backend, 
RESTful APIs adhere to the principles of Representational State Transfer (REST), 
offering a standardized and scalable approach for designing web services that support various HTTP methods (GET, POST, PUT, DELETE) and data formats (JSON, XML).

Socket.IO: Integrated for real-time communication between clients and the server,
Socket.IO enables bidirectional event-based communication, 
allowing users to interact with each other in real-time through features such as chat messaging and notifications.

APIs and Endpoints:

Authentication Endpoints: Includes endpoints for user authentication and authorization, 
such as registration, login, logout, and token validation.

User Management Endpoints: Provides endpoints for managing user profiles, including CRUD operations for user information,
profile pictures, and account settings.

Social Media Functionality Endpoints: Encompasses endpoints for social interactions, 
such as posting, liking, commenting, sharing, following, and unfollowing other users.

Real-time Communication Endpoints: Facilitates real-time messaging and notifications through WebSocket-based endpoints powered by Socket.IO,
allowing users to engage in instant communication and receive updates in real-time.

## Socket.IO Repository
- Link to the Socket.IO repository: [Socket.IO Repository](https://github.com/DilshaMujeeb/Social_Media_socket.io)
The Socket.IO repository houses the server-side implementation for real-time communication in the ReelKing application.
It provides the infrastructure for enabling instant messaging, notifications, and other real-time features through WebSocket-based endpoints.

## Setup Instructions

Prerequisites:
Ensure you have Node.js and npm installed on your machine.
You need to have MongoDB installed and running locally or have access to a MongoDB instance.

Setup Instructions:
Clone the Repository:
Clone the project repository from GitHub using the following command:
git clone <repository_url>

Navigate to Frontend and Backend Directories:
cd client
cd server
cd socket.io  

Install Dependencies:
Inside both the frontend and backend directories, install the required dependencies using npm:
npm install

Configuration:

Backend: Update the .env file with your MongoDB connection string and any other necessary configurations.
Frontend: If needed, adjust configuration files for environment variables like API endpoints.

Run the Backend Server:
Start the backend server by running the following command in the backend directory:
npm start

Run the Frontend Application:
Open a new terminal window, navigate to the frontend directory, and start the frontend application:
npm start

Run Socket.io Server:
Open a new terminal window, navigate to the socket.io directory, and start:
npm start


Access the Application:
Once both the backend and frontend servers are running, you can access the ReelKing application by opening your web browser and 
navigating to http://localhost:3000 (or the specified port if configured differently).




## Additional Resources

Additional Notes:
Make sure MongoDB is running locally or configure the backend to connect to a remote MongoDB instance.
You may need to install additional dependencies or troubleshoot any errors based on your local environment configuration.
