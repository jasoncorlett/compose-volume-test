# Compose Volume Test

Example of sharing application code from one container to another.

## Usage

### Run

```docker-compose up -d --build```

Navigate to: http://localhost

Defaults to port 80, change in [docker-compose.yml](./docker-compose.yml) if needed.

### Clean Up

```docker-compose down -v --rmi local```
