<!-- Write README.md docker compose -->
# MongoDB Docker Setup

This repository provides a basic setup for running MongoDB using Docker. The configuration utilizes Docker Compose to set up and run a MongoDB container with persistent storage.

## Prerequisites

Make sure you have the following installed:

- Docker: [Installation guide](https://docs.docker.com/get-docker/)
- Docker Compose: [Installation guide](https://docs.docker.com/compose/install/)

## Setup Instructions

1. **Clone this repository**

   ```sh
   git clone <repository_url>
   cd food-delivery-compose
   ```
   
2. **Run MongoDB with Docker Compose**

  Run the following command to start MongoDB:

  ```sh
  docker-compose up -d
  ```
  This command will pull the official MongoDB image from Docker Hub and set up a container with the specified settings.

3. **Access MongoDB**

  - MongoDB will be accessible on localhost:27017.

  - You can connect using the MongoDB CLI, Compass, or any MongoDB client using the following credentials:
  
    Username: root
    Password: example

