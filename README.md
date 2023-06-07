# DocManageSystem Deployment

## Description

This project contains a Docker Compose configuration to run the whole DocManageSystem.

## Prerequisites

- Docker Engine: Make sure you have Docker Engine installed on your machine. You can download and install Docker from the official website: https://www.docker.com/get-docker

## Getting Started

1. Clone the repository:
  ```shell
  git clone --recursive  https://github.com/cloud-native-documentation/documentation-deployment
  ```
2. Navigate to the project directory:
  ```shell
  cd documentation-deployment
  ```
3. Build the Docker images and start the containers:
  ```shell
  docker-compose up --build -d
  ```
  
## Configuration
The Docker Compose configuration may include environment variables or other configuration options. You can modify these settings by updating the .env file or the relevant environment variables in the docker-compose.yml file.

## Cleanup
To stop and remove the Docker containers created by the Compose configuration, you can run the following command:
  ```shell
  docker-compose down
  ```
