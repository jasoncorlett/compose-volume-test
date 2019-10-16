# Compose Volume Test

Example of sharing application code from one container into another at runtime.

## Usage

### Run

```docker-compose up -d --build```

### View

Navigate to: http://localhost

Defaults to port 80, change in `docker-compose.yml` if needed.

### Clean Up

```docker-compose down -v --rmi local```
