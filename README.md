# Containerized Full-Stack Web Application Deployment with MongoDB and AWS ECR

# Project Overview
  This project demonstrates the deployment of a full-stack web application using Docker containers. The application features a Node.js backend and a frontend built with HTML and JavaScript. MongoDB is used as the     database, with Mongo Express providing a user-friendly UI for managing the database. The project uses Docker Compose for container orchestration and AWS Elastic Container Registry (ECR) for hosting the Docker images.

# Features
  Frontend (HTML, JavaScript): Provides a dynamic user interface for interacting with the application.
  Node.js Backend: Handles server-side operations and interacts with the MongoDB database.
  MongoDB: Serves as the database for storing application data.
  Mongo Express: Provides an intuitive UI to manage MongoDB.
  Docker Compose: Manages the frontend, backend, and database containers, including persistent volumes.
  AWS ECR: Hosts the Docker image for scalable and secure storage.

 # Project Structure
  /project-root
    |-- Dockerfile (for the Node.js app)
    
    |-- docker-compose.yml (for managing containers)
    
    |-- /src (source code for the frontend and backend)
    
    |-- /data (MongoDB data stored via Docker volume)

# Technologies Used
  -Frontend: HTML, JavaScript
  
  -Backend: Node.js
  
  -Database: MongoDB, Mongo Express
  
  -Containerization: Docker, Docker Compose
  
  -Cloud Services: AWS ECR
