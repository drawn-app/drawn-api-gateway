# Drawn - API Gateway

This API gateway is implemented by using Kong Gateway, open source API gateway, with some custom plugins.

## Installation

- Build docker image of this gateway

```
docker build -t custom-gateway:1.0 .
```

- Create containers from docker compose config file

```
docker compose up -d
```

- Import volume file to `api-gateway_kong_data`

## Usage

- API entry point: port 8000
- Admin GUI: port 8002