# Tadeo Sorrentino

**Backend & AI/Agent Engineering** · Java · Spring Boot · TypeScript

Software Engineer at **WirData** · Information Systems Engineering student at **UTN FRBA** (CGPA 8.94/10) · programming since 2016

[Portfolio](https://tsorren.github.io) · [LinkedIn](https://www.linkedin.com/in/tadeo-sorrentino/) · [Email](mailto:tadeosorrentino@gmail.com)

## Now at WirData

- Contributed to refactoring multi-tenant services of a centralized IaaS and SaaS platform: an IAM service that decouples Keycloak authentication from RBAC/ABAC authorization, and a virtualization microservice restructured around DDD (TypeScript, Kubernetes, Galera).
- Designed a transactional resource allocation strategy over RabbitMQ (eventual consistency) and cut the CI/CD deployment cycle from ~21 min to 3–5 min with Testcontainers in GitHub Actions.
- Developed and deployed a custom Odoo 19 CRM module (Python) for an external client as sole maintainer, with 98% test coverage and Playwright E2E tests; in production since November 2026.

## Featured projects

| Project | What it is | Stack |
|---|---|---|
| [DonaTrack](https://github.com/tsorren/DonaTrack-TP-DDS) · 2026 | 5 event-driven microservices under Clean Architecture (layer rules enforced by ArchUnit), with RabbitMQ outbox, retries and idempotency. Team of 9; owner of the inter-service contracts. | Java 21, Spring Boot 4, RabbitMQ, PostgreSQL, Keycloak |
| [Metamapa](https://github.com/tsorren/Metamapa-TP-DDSI) · 2025 | 5 microservices (aggregator, statistics, and static, dynamic and proxy data sources), with RBAC, a state machine to audit geolocated reports and server-side rendering. | Java, Spring Boot, Spring Security, MySQL, Docker |
| [Distributed OS Simulation](https://github.com/tsorren/OS-Simulation-TP-SSOO) · 2025 | Distributed UNIX OS simulator: FIFO/SJF/SRT scheduling, paging with SWAP and concurrent communication over HTTP. | Go, Linux |
| [Advanced Programming Techniques](https://github.com/tsorren/Paradigmas-Avanzados-TP-TADP) · 2025 | Runtime Design-by-Contract framework through Ruby metaprogramming, and an immutable tournament engine in Scala. | Ruby, Scala |

Also: [Sofa Factory](https://github.com/tsorren/Fabrica-de-Sillones-TP-BBDD) (data migration and OLAP star schema on SQL Server) · [Tienda Sol](https://github.com/tsorren/Tienda-Sol-TP-DDSO) (MERN e-commerce tested with Jest and Cypress)

## AI & agent engineering

- Implemented an AI Agent Governance Framework (context router) that cut token usage by over 65%.
- Deployed the admin stack of a hybrid AI platform: LiteLLM as the model gateway, PostgreSQL and Hermes Agent, with local models served by vLLM on NVIDIA T4 GPUs.
- Developed the Odoo module above by directing AI agents through specs and PR audits (spec-driven development).

## Stack

- **Backend:** Java, Spring Boot, Spring Security, Spring Cloud Gateway, TypeScript, Node.js, Express
- **Messaging & data:** RabbitMQ, PostgreSQL, MySQL, MariaDB, SQL Server, MongoDB, Redis
- **Testing:** JUnit, Mockito, Testcontainers, ArchUnit, Pitest, Jest, Cypress, Playwright
- **DevOps:** Docker, Kubernetes, GitHub Actions, SonarQube, Linux
- **AI:** LiteLLM, vLLM, MCP servers, context engineering
