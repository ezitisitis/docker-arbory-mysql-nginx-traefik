# Docker Compose for Arbory with Traefik

This is Docker Compose for Arbory projects (PHP + MySQL + NGINX) which are
runing behind Traefik.

## Requirments

- Docker compose
- Docker container with configured traefik

## Setup

Add environment data.

```bash
cp .env.sample .env
vi .env
```

## Run

### Development

```bash
docker-compose -f docker-compose-development.yml up -d
```

### Production

```bash
docker-compose up -d
```
