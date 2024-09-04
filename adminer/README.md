
#### Connecting local databases

```yaml
# network_mode: host # this works with localhost:5432, but can not change adminer port from 8080
networks:
    - external-host # for postgres-dev:5432
```