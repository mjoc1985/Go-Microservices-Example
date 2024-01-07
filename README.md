# Go Microservices Examples
This repo contains multiple small microservices written in Go and configured to be deployed to either Kubernetes or Docker Swarm as part of my learning journey. 
It contains a simple frontend that allows you to trigger each of the services which all work using various methods of communication such as RPC, gRPC, and RabbitMQ.

Contains a docker swarm configuration.

## Get started
The commands to build and run are in the project folder and ensure docker is running.

``cd /project``

### Run build command

`` make up_build ``

This will build all of the projects and start docker-compose

### Start all containers

`` make start ``

Starts all of the containers without forcing a build

### Stop all containers

`` make down ``

Stops docker-compose

### Start frontend

`` make start ``

Starts the frontend app

### Stop frontend

Stops the frontend app

`` make stop ``
