# Dockerized PHP Application with AWS RDS Integration

## Overview
This repository contains a simple PHP application that has been Dockerized and deployed on an AWS EC2 instance. The application interacts with a MySQL database hosted on AWS RDS (Relational Database Service). The primary goal of this project is to demonstrate the use of Docker for containerization and AWS services for deployment and database management.

## Features
PHP Application: A basic PHP application that performs CRUD (Create, Read, Update, Delete) operations.
Dockerized: The application is packaged in a Docker container for easy deployment and scalability.
AWS RDS Integration: The application connects to a MySQL database hosted on AWS RDS, ensuring reliable and scalable database management.
Manual Deployment on AWS EC2: The Docker container is manually deployed on an AWS EC2 instance, showcasing the process of setting up and running a containerized application on a cloud-based virtual machine.
CI/CD Pipeline: The project can be extended to include a Continuous Integration and Continuous Deployment (CI/CD) pipeline using Jenkins. Jenkins automates the build and deployment process, integrating with GitHub to pull the latest code, build the Docker image, and deploy it to an AWS EC2 instance.

## Technologies Used
## PHP: Backend scripting language for web development.
## Docker: Containerization platform to package the application.
## MySQL (AWS RDS): Managed database service for storing application data.
## AWS EC2: Virtual machine for deploying the Docker container.
## AWS RDS: Relational Database Service for hosting the MySQL database
