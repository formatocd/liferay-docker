# Liferay Docker Project

This project sets up a Liferay 7.4.3.129 with PostgreSQL 16 environment using Docker. The configuration is defined in the `docker-compose.yml` file.

## Prerequisites

- Docker
- Docker Compose

## Usage

1. Clone the repository:
     ```sh
     git clone https://github.com/yourusername/liferay-docker.git
     cd liferay-docker
     ```

2. Start the services:
     ```sh
     docker-compose up -d
     ```

3. Access Liferay at [http://localhost:8080](http://localhost:8080).

## Stopping the Services

To stop the services, run:
```sh
docker-compose down
```

## License

This project is licensed under the MIT License.