# Microservices-e-commerce
This is our project for the advanced operating systems course. It's a microservice-based e-commerce website made to manage the shopping modules efficiently by using different microservices as their modules. the method and necessary details are given below.


*Follow these steps to run the code defined in the code blocks:*

Here’s a step-by-step guide to setting up and running the backend code, including Docker and Kubernetes deployment. I’ve reviewed and made sure there’s no syntax or configuration error. This guide assumes you have Node.js, Docker, Kubernetes (Minikube or any Kubernetes cluster), and kubectl installed.

Here’s a step-by-step guide to setting up and running the backend code, including Docker and Kubernetes deployment. I’ve reviewed and made sure there’s no syntax or configuration error. This guide assumes you have **Node.js**, **Docker**, **Kubernetes (Minikube or any Kubernetes cluster)**, and **kubectl** installed.

Step 1: Set Up MySQL Database in Docker
1.1 Run MySQL in Docker:

Step 2: Backend Application Setup (Node.js with Express)
2.1 Create a project directory:
2.2 Initialize the Node.js project:
2.3 Install necessary packages:
2.4 Create an index.js file and paste the code defined in the code block with the same heading name:
2.5 Run the application:

Step 3: Dockerize the Application
3.1 Create a Dockerfile in the project root:
3.2 Build and run the Docker container:

Step 4: Kubernetes Setup (Minikube or Kubernetes Cluster)
4.1 Create Backend Deployment in Kubernetes:
4.2 Create MySQL Deployment in Kubernetes:
4.3 Deploy to Kubernetes:
4.4 Expose the Services:
4.5 Access the Backend Service:


Summary Checklist
MySQL Setup - Confirm MySQL Docker container is running.
Node.js App - Confirm backend server runs locally without errors.
Docker Build - Ensure Docker container builds and runs successfully.
Kubernetes Deployment - Check the deployments and services run in Kubernetes.
This guide ensures a complete backend setup for your prototype with integrated MySQL, Docker, and Kubernetes. Thank you!


