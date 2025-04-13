#  Grafana Logging & Monitoring Stack

This repository sets up **Grafana** and **Prometheus** using Docker Compose to monitor metrics from Spring Boot microservices via `/actuator/prometheus`.

---

##  Project Structure
```
grafana-logging/ 
├── docker-compose.yml 
└── prometheus/ 
  └── prometheus.yml
```
---

##  Getting Started

```bash
https://github.com/Green-Pulse/grafana-logging.git
cd grafana-logging
docker-compose up -d
```

Prometheus → http://localhost:9090

Grafana → http://localhost:3000 (login: admin / admin)

