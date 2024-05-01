# MongoDB & Express.js Application on Kubernetes

This project demonstrates the deployment of a basic MongoDB and Express.js web application on Kubernetes. It includes the configuration of deployment and service resources for both MongoDB and Express.js components. Additionally, Kubernetes secrets are utilized for storing sensitive data such as usernames and passwords, while config maps are employed for managing database connection settings.

## Technologies Used

- **MongoDB**: A NoSQL database used for data storage.
- **Express.js**: A minimal and flexible Node.js web application framework.
- **Kubernetes**: An open-source container orchestration platform for automating deployment, scaling, and management of containerized applications.

## Project Overview

1. **Application Development**:
   - A simple web application is developed using Express.js for the backend and MongoDB for data storage.

2. **Containerization with Docker**:
   - Docker containers are created for both the Express.js application and the MongoDB database to ensure consistency across different environments.

3. **Kubernetes Deployment and Service**:
   - Kubernetes deployment manifests are defined for both the Express.js application and the MongoDB database.
   - Kubernetes service resources are configured to enable communication between application components and external access to the web application.

4. **Secrets Management**:
   - Kubernetes secrets are used to securely store sensitive data such as usernames and passwords for database access.

5. **Configuration Management**:
   - Kubernetes config maps are employed to manage database connection settings, providing flexibility and ease of configuration.
