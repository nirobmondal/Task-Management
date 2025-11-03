# Task Management

A simple RESTful API for managing tasks, built with Node.js and Express.

## Setup and Installation

1.  Clone the repository to your local machine.
2.  Install the required dependencies using npm:
    ```sh
    npm install
    ```

## Running the Application

To start the server, run the following command from the project root:

```sh
npm start
```

The server will start and listen on `http://localhost:3000`.

## API Endpoints

The following endpoints are available:

- `GET /`: Displays a welcome message to confirm the API is running.
- `GET /tasks`: Retrieves a list of all tasks.
- `GET /task/:id`: Retrieves a single task by its unique ID.
- `GET /health`: Returns the health status and uptime of the application.
