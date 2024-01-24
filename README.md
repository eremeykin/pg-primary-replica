# Single-Primary PostgreSQL Replication with Docker-compose
# Article with code explanations: [How to Setup Single-Primary PostgreSQL Replication with Docker-compose](https://medium.com/@eremeykin/how-to-setup-single-primary-postgresql-replication-with-docker-compose-98c48f233bbf)

Run primary and replica in background:
```bash
docker-compose up -d postgres_primary postgres_replica
```

Stop all services and remove volumes:
```bash
docker-compose down -v
```
