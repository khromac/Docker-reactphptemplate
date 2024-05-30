# HDI-react Project Template

This is a template for a project with a React frontend, PHP backend, PHPMyAdmin, and MySQL, all running in Docker.

## Setup

### Prerequisites

- Docker
- Docker Compose

### Installation

1. Clone the repository:

    ```bash
    git clone <remote-repository-URL>
    cd HDI-react
    ```

2. Update environment variables and configuration files as needed.

3. Build and start the containers:

    ```bash
    docker-compose up --build -d
    ```

4. Access the services:
    - React App: `http://localhost:3000`
    - PHP Backend: `http://localhost`
    - PHPMyAdmin: `http://localhost:8080`

### Usage

Make your changes in the `frontend/src` directory for the React app and the `backend` directory for the PHP backend. Changes will be reflected automatically.

### Notes

- Ensure `CHOKIDAR_USEPOLLING=true` is set in the `docker-compose.yml` for live reloading of the React app.
- Update the `Dockerfile` and `docker-compose.yml` as needed for your specific use case.

## License

[MIT License](LICENSE)
