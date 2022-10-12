# static-server

Uses docker compose to run a simple apache server to serve a static application.

## Usage

You should simply put your static application files on `deploy/` directory and then execute docker compose:

- For v2.10.2 and higher:

`docker compose -f ./docker-compose.yaml -p static-server up --build`

- For docker-compose version 1.29.2:

`docker-compose -f ./docker-compose.yaml -p static-server up --build`

<sub>You can also add `-d` parameter in order to run it deatached.</sub>

### Requirements

- Docker CE
- Docker Compose
