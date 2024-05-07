# Cafe Sanchez
**Demo Application for PWU**

This application consist of three main components:

1. **Front-end Application:** A Node.js application using Express and EJS as the view engine.
2. **REST API:** Another Node.js application with Express that serves as the backend API.
3. **MySQL Database:** A MySQL instance running in a Docker container.

## Directory Structure

Here’s how the project directory is structured:

```
/my-web-app
|-- /api                   # API source files
|   |-- server.js          # Entry point for the API server
|   |-- /routes            # API routes
|   `-- /controllers       # API logic
|-- /web                   # Web application source files
|   |-- app.js             # Entry point for the web server
|   |-- /views             # EJS templates
|   |-- /public            # Static files like CSS, JavaScript, images
|   `-- /routes            # Web app routes
|-- /database              # Scripts for creating the database
|-- /docker-compose.yml    # Docker compose file to orchestrate containers
`-- /README.md             # Project documentation
```

## Setting Up the Application

### API

### Web Frontend

### Database

https://hub.docker.com/_/mysql

## Running the Application
