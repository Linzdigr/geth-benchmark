# Kiwi benchmark tester (containerized)

### Prerequisites
- Docker
- (Docker Compose) -> Should be now embedded into Docker

### Run it
```sh
# Sysbench
docker-compose up -d sysbench
docker-compose logs -f

# FIO
docker-compose up -d fio
docker-compose logs -f
```
