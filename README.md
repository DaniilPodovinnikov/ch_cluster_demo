# DEMO Clickhouse Cluster

Демо кластер Clickhouse: 2 шарда по 2 реплики

## Запуск
```sh
docker compose up -d
```

## Запуск клиента
```sh
docker exec -it clickhouse01 clickhouse-client
```

## Profiles

- `default` - no password