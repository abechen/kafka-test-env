# Kafka Test Env

## Install env

- Check you have docker engine on you computer.

```=shell
# Verify Docker readiness
docker --version

docker-compose --version
```

- Execute:

```=shell
# Start services
docker-compose up -d

# Verify services
docker-compose ps
```

- Base on docker-compose.yml, it will start docker images including:
  - kafka
  - zookeeper
  - schema registry
  - kafdrop

