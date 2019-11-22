# {app.name}

The helm chart of {app.name}.

## TL;DR

```bash
$ helm install {app.name}
```

## Configuration

The following tables lists the configurable parameters of the {app.name} chart and their default values.

| Parameter                        | Description                                             | Default                                                      |
|----------------------------------|---------------------------------------------------------|--------------------------------------------------------------|
| `image.repository`               | Docker image name                                       | `{app.name}:latest`                                       |
| `service.type`                   | Service type                                            | `NodePort`                                                   |
| `postgresql.postgresqlDatabase`  | database name                                           | `user`                                                       |
| `postgresql.postgresqlUsername`  | database user                                           | `postgres`                                                   |
| `postgresql.postgresqlPassword`  | database password                                       | `password`                                                   |