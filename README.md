# Throughput vs Pathloss

Web app for computing and displaying throughput vs path loss.

## Requirements

To run the application, install [Node.js](https://nodejs.org/en/) version **>=14.0.0** with [npm](https://www.npmjs.com/) version **>=8.15.0** and [Python](https://www.python.org/) version **>=3.0**.

### Setup Development Environment

To start the development environment via terminal or command-line:
1. To start the client application, run:
    ```sh
    cd client && npm install && npm start
    ```
2. In another terminal, start the server with:
    ```sh
    cd server && pip install -r requirements.txt && python app.py
    ```
3. The app runs on [http://localhost:3000](http://localhost:3000).

## Requirements Using Docker and Docker Compose

To run the application via Docker, [Docker Engine](https://docs.docker.com/engine/install/) and [Docker Compose](https://docs.docker.com/compose/install/) must be installed. Alternatively, [Docker Desktop](https://docs.docker.com/compose/install/compose-desktop/) can be downloaded, which includes both [Docker](https://docs.docker.com/engine/) and [Docker Compose](https://docs.docker.com/compose/).

### Setup Development Environment

To start the development environment:
1. Run `docker-compose up` to start the app in development mode. If this is the first time you run it, Docker will need to build the container.
2. The app runs on [http://localhost:3000](http://localhost:3000).

### Setup Production Environment

To start the production environment:
1. Run `docker-compose -f docker-compose.yml up -d` to start the app in production mode. If this is the first time you run it, Docker will need to build the container.
2. The app runs on [http://localhost:80](http://localhost:80).
