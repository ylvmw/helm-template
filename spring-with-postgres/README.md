# spring-with-postgres

The helm chart of spring-with-postgres.

## TL;DR

```bash
$ helm install spring-with-postgres
```

## Configuration

The following tables lists the configurable parameters of the spring-with-postgres chart and their default values.

| Parameter                        | Description                                             | Default                                                      |
|----------------------------------|---------------------------------------------------------|--------------------------------------------------------------|
| `image.repository`               | Docker image name                                       | `spring-with-postgres:latest`          |
| `service.type`                   | Service type                                            | `NodePort`                                                   |
| `postgresql.postgresqlDatabase`  | database name                                           | `spring-with-postgres`                                                       |
| `postgresql.postgresqlUsername`  | database user                                           | `postgres`                                                   |
| `postgresql.postgresqlPassword`  | database password                                       | `password`                                                   |