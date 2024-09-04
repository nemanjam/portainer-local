
#### Connecting local databases

Because Adminer is container that has isolated network, and host is bound ot 5432.

```yaml
# network_mode: host # this works with localhost:5432, but can not change adminer port from 8080
networks:
    - external-host # for postgres-dev:5432
```