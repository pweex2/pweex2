# 👋 Hi, I’m Wayne

> **Golang Backend Engineer | Distributed Platforms for Network Automation & Traffic Control | Singapore PR**

Golang Backend Engineer focused on building reliable, scalable distributed platforms for network automation and traffic control, with hands-on experience in CDN and large-scale control systems.

I specialize in backend and platform engineering, architecting **Control Planes** and **Execution Engines** that turn complex routing and policy logic into automated, high-performance systems operating at scale.

Experienced in running production systems with **Redis, ClickHouse, Prometheus, Elasticsearch, and etcd**, with a strong emphasis on reliability, observability, and operational correctness.

---

## 🛠 Tech Stack

| Category | Technologies |
|----------|--------------|
| **Languages** | **Golang** (Core), Java, Shell Scripting |
| **Architecture** | Microservices, Event-Driven Architecture (EDA), **Distributed Transactions** (Saga, Outbox Pattern) |
| **API & Protocols** | **RESTful API Design**, RPC, HTTP/HTTPS |
| **Cloud Native & DevOps** |  **Docker**, **GitHub Actions** (CI/CD), **OpenTelemetry** (Distributed Tracing), Jaeger |
| **Middleware & Storage**| **etcd** (Service Discovery, Configuration), Redis, RabbitMQ, MySQL , ClickHouse, Elasticsearch |

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

### 🛒 [Distributed E-commerce Microservices System](https://github.com/pweex2/vv-ecommerce)
> *A scalable microservices backend focusing on data consistency and observability.*

Designed and developed a robust backend (Order, Inventory, Payment, Gateway) tackling distributed system challenges.

*   **Distributed Transactions**: Engineered reliable consistency using **Transactional Outbox** and **Saga Patterns**, solving "Dual-Write" issues between MySQL and RabbitMQ.
*   **Full-Stack Observability**: Integrated **OpenTelemetry** and **Jaeger** for end-to-end distributed tracing, enabling rapid latency diagnosis.
*   **High-Concurrency**: Implemented idempotent consumers and exponential backoff retries. Optimized Outbox Processor with `SKIP LOCKED` for horizontal scaling.
*   **Tech**: Golang, RabbitMQ, Docker, MySQL, OpenTelemetry.

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
