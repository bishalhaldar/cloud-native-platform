# Cloud Native Platform

A small local cloud-native stack using Docker Compose

Includes:
- Weather API container
- Prometheus monitoring

---

## Services

### Weather API
Runs the Node.js weather API container.

Port:
3000

Test:

http://localhost:3000/weather-api?city=<city-name>

---

### Prometheus

Prometheus collects metrics from the weather API.

Port:
9090

UI

https://localhost:9090

---

## Run the platform

Start services:

docker compose up

Stop services:

docker compose down