# Docker configuration
## Laravel app configured with PostgreSQL using Docker containers

- Run command: `docker-compose up --build -d`
- Run the container in bash mode: `docker exec -it Laravel_php /bin/sh`
- You can access the project at: `http://localhost:8000`
- Stop all running containers at once: `docker kill $(docker ps -q)`
