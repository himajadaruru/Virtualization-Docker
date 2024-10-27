# Dockerized Nginx Server

## Overview
This project sets up a basic Nginx server running in a Docker container.

## Prerequisites
- Docker Desktop installed on local machine.

## Setup Instructions

1. Clone the repository:
   git clone https://github.com/himajadaruru/Virtualization-Docker.git

   cd my-docker-nginx

2. Build the Docker image:
   docker build -t my-nginx-image .
   
3. Run the Docker container:
   docker run -d -p 80:80 --name my-nginx-container my-nginx-image
   
4. Access the service: Open web browser and navigate to http://localhost.
