# 👋 Hi, I’m Wayne

> **Golang Backend Engineer | Distributed Platforms for Network Automation & Traffic Control | Singapore PR**

Golang Backend Engineer focused on building reliable, scalable distributed platforms for network automation and traffic control, with hands-on experience in CDN and large-scale control systems.

I specialize in backend and platform engineering, architecting **Control Planes** and **Execution Engines** that turn complex routing and policy logic into automated, high-performance systems operating at scale.

Experienced in running production systems with **Redis, ClickHouse, Prometheus, Elasticsearch, and etcd**, with a strong emphasis on reliability, observability, and operational correctness.

---

## 🧠 Core Skills

- **Languages**: Golang (primary), Java
- **Databases**: Microservices, Event-Driven Architecture, REST
- **Infrastructure**: Docker, GitHub Actions, etcd, RabbitMQ
- **Architecture**: Modular design, event-driven, distributed systems

---

## 🛠 Tech Stack

| Category | Technologies |
|----------|--------------|
| **Languages** | **Golang** (Primary), Java |
| **Backend** | Microservices, Event-Driven Architecture, RPC, REST |
| **Data** | MySQL, Redis, ClickHouse, Elasticsearch, etcd |
| **Infra & Ops** | Docker, GitHub Actions, RabbitMQ, Systemd, Linux |

---

## 🚀 Featured Projects

### 🌐 GP Coordination – Intelligent Traffic Scheduling Control Plane
> *Based on the [Auto-Scheduling System 4.0](https://github.com/ryzh3n/cdn-scheduling-system) philosophy.*

A high-performance **Control Plane** designed to act as the "brain" of a CDN. It ensures service availability and optimal routing through an automated **Observation → Analysis → Execution** loop.

*   **Smart Scheduling**: Implements Geo-Routing, Latency-Based Selection, and Weighted Load Balancing.
*   **Automated Failover**: Real-time detection of node failures with instant DNS-based traffic rerouting.
*   **Hybrid Control**: Supports fully automated rule-based decisions + granular manual dispatch (`g->y->IP`).
*   **Tech**: `Asynq` (Scheduling), `Rule Engine` (Logic), `Redis` (State), `etcd` (Config).


[👉 Check Details](./coordination-details.md)

[👉 Check Architecture Diagram](./coordination.drawio)

---

### ☀️ Solar-portal – IoT Edge Gateway
> *Embedded data collector for solar energy monitoring, optimized for edge devices (Raspberry Pi).*

An efficient edge gateway that bridges industrial protocols with modern big data pipelines.

*   **Edge Computing**: Collects real-time data via `Modbus` (RTU/TCP) and processes it locally.
*   **Data Pipeline**: Pushes normalized data to `Solar-Stream` -> ClickHouse / Elasticsearch.
*   **Reliability**: Lightweight auto-installer with systemd integration and watchdog mechanisms.
*   **Tech**: Golang, Modbus, REST API.

---

## 📫 Reach Me

- LinkedIn: [Wayne Puah](https://www.linkedin.com/in/wayne-puah/)
- GitHub: [@waynepuah](https://github.com/vvx2)
