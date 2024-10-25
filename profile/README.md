# Todennus

An Identity, OpenID Connect, and OAuth2 Provider.

## Documentations

[API Refereneces](https://github.com/todennus/docs/tree/dev/references.md)

[Resources](https://github.com/todennus/docs/tree/dev/resources.md)

[Swagger Endpoint](https://github.com/todennus/docs)

[gRPC Services](https://github.com/todennus/proto)

### Architecture

- Multirepo miroservices.
- Clean architecture.
- Domain driven development.
- Event driven architecture.

## Tech stack

- Database: [gorm](https://github.com/go-gorm/gorm), [go-migrate](https://github.com/golang-migrate/migrate), [postgreSQL](https://www.postgresql.org/), [redis](https://redis.io/).
- Mux: [go-chi](https://github.com/go-chi/chi).
- RPC: [gRPC](https://grpc.io/).
- Docs: [swaggo](https://github.com/swaggo/swag).
- Container: [Docker](https://www.docker.com/).
- Deployment: [Docker compose](https://docs.docker.com/compose/).

## Target

### Features

- OAuth2 Provider with:
  + Authorization Code Flow ***\*completed\****.
  + Authorization Code Flow With PKCE ***\*completed\****.
  + Implicit Flow.
  + Resource Owner Password Credentials Flow ***\*completed\****.
  + Client Credentials Flow.
  + Refresh Token Flow ***\*completed\****.
  + Device Flow (low priority).

- Support Open ID Connect.
- Allow integrate with external Identity/OAuth2 Provider ***\*completed\****.

### User traffic

- 100M users.
- 1M new users per day.
- 10M OAuth2 requests per day.
