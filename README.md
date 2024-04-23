# E-commerce Microservices Application


PROJECT CONTIRBUTED BY TEAM:
PES2UG22CS818:Sankalp Taral




PES2UG22CS817:RAKESH


PES2UG22CS816:Ranjitha

PES2UG21CS363:Pannaga

Under The Guidance of 
Prof.Pavithra

## Overview

This project aims to develop an E-commerce Microservices Application that can be deployed on the cloud using Docker, Kubernetes, Jenkins, and Git. The application will consist of several microservices that will be deployed as Docker containers on a Kubernetes cluster. Jenkins will be used for continuous integration and deployment, while Git will be used for version control.

## Objectives

### Week 1: Microservices Architecture Design and Development

- Define microservices that will be part of the application.
- Determine communication protocols between microservices.
- Plan data models and schemas for each microservice.
- Design and implement the microservices architecture for the application.
- Create Docker containers for each microservice.
- Use Kubernetes to orchestrate the containers locally.
- Implement a Jenkins pipeline to automate the deployment process.
- Integrate Git with Jenkins to trigger the pipeline on code changes.
- Develop microservices using appropriate programming languages and frameworks.
- Implement REST APIs to allow communication between the microservices.

### Week 2: Containerization and Orchestration

- Write Dockerfiles for each microservice.
- Build and test Docker images for each microservice.
- Create Kubernetes deployment manifests for each microservice.
- Set up Kubernetes services for each microservice.
- Test and validate the Kubernetes deployment.

### Week 3: Continuous Integration and Deployment

- Setup Jenkins on a server.
- Create Jenkins jobs and corresponding Jenkinsfiles for building, testing, and deploying microservices.
- Configure Jenkins to monitor the Git repository for changes and trigger automatic builds and deployments.
- Utilize Git for version control, managing different versions and branches of the codebase.

## Microservices Modules

- **User Management:** Handles the registration, authentication, and authorization of users. Allows users to create accounts, login, and manage their profiles.
- **Product Management:** Handles the management of products. Allows admins to add, edit, and delete products. Also allows users to view and search for products.
- **Order Management:** Handles the management of orders. Allows users to view their order history, track their orders, and manage their orders.
- **Review Management (optional):** Handles the management of product reviews. Allows users to view and add reviews for products.

## Deliverables

- Microservices architecture document.
- Codebase for implemented microservices with REST APIs.
- Docker images for each microservice.
- Kubernetes deployment manifests and services.
- Jenkins jobs and configuration files.
- Automated builds and deployments triggered by Git commits.
