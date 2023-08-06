# Single-Primary PostgreSQL Replication with Docker-compose

Run primary and replica in background:
```bash
docker-compose up -d postgres_primary postgres_replica
```

Stop all services and remove volumes:
```bash
docker-compose down -v
```