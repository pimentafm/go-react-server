# Backend Go

## How to use

- Rename `env_example` to `.env`
- Run docker compose to spin up postgresql and pgadmin4 `docker compose up -d`


## Dependencies

### tern

- Install `go install github.com/jackc/tern/v2@latest`
- Init tern `tern init ./internal/store/pgstore/migrations/`
- Create migrations `tern new --migrations ./internal/store/pgstore/migrations/ create_rooms_table` 


