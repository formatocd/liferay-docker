# Liferay Docker Project
This project sets up a Liferay Portal with PostgreSQL or MySQL environment using Docker. The configuration is defined in the `docker-compose.yml` file.

## Prerequisites
- Docker
- Docker Compose

## Usage
1. Clone the repository:
     ```sh
     git clone https://github.com/formatocd/liferay-docker.git
     cd liferay-docker
     ```
2. Start the container:
     ```sh
     docker-compose up -d
     ```

3. Access Liferay at [http://localhost:18080](http://localhost:18080).

## Stopping the Services

To stop the services, run:
```sh
docker-compose down
```

## License
This project is licensed under the MIT License.