# Flutter Web with Docker

This project demonstrates how to deploy a Flutter web application using Docker Compose. It includes a Flutter app served by a Flutter development container and an NGINX container to serve the compiled Flutter web build.

## Prerequisites

- Docker
- Docker Compose

## Getting Started

1. Clone the repository:

   ```bash
   git clone 

2. Navigate to the project directory:
   ```bash
   cd 

3. Build and run the containers:
   ```bash
   docker-compose up

4. Access Flutter_appe continer then:
   ```bash
   cd ..
   flutter create app
   cd app
   flutter build web

5. Access the Flutter web app:
    Open http://localhost:83 in your web browser to view the Flutter web app.


## Usage

- To start the containers: `docker-compose up`
- To stop the containers: `docker-compose down`


