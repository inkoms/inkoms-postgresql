# inkoms-postgresql

Quickstart's Docker Compose PostgreSQL with PgAdmin
This repo works with [inkoms-vagrant-local][inkoms-vagrant-local]

## Requirements

- Docker compose

## Steps

### 1. Clone the repository

```shell
git clone https://github.com/inkoms/training-postgresql
cd inkoms-postgresql
```

### 2. Set environment variables

Create a `.env` from `.env.example` file in the root folder with all environment variables, this variables will be used by the containers, it need to be reached by `docker-compose.yml` file.

### 3. Run

```shell
docker compose -p inkoms-posgresql up -d
```

After type and run the command go to `localhost:${PG_ADMIN_PORT}`

[inkoms-vagrant-local]: https://github.com/inkoms/inkoms-vagrant-local