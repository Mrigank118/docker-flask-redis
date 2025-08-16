```markdown
# Flask + Redis Docker Example

A simple Dockerized Flask app that counts visitors using Redis.

## How to Run

1. Build and start containers:

```
docker-compose up --build
```

2. Open in browser:

```
http://localhost:5000
```

## Stop Containers

```
docker-compose down
```

## What It Does

- Flask app increments a visitor count stored in Redis.
- Redis data is persisted using Docker volumes.
- Both run in separate containers managed by Docker Compose.

---
```