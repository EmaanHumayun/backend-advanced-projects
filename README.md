# Level 3: Advanced Systems

[![Main Hub](https://img.shields.io/badge/Central%20Hub-backend--engineering--hub-1F2937?style=flat-square&logo=github)](https://github.com/EmaanHumayun/backend-engineering-hub)
[![Maintainer](https://img.shields.io/badge/Maintainer-Emaan%20Humayun-blue?style=flat-square)](https://github.com/EmaanHumayun)

Five advanced backend projects covering modular architecture, API gateways, real-time communication, caching, performance, testing and security.

Part of the **[Backend Engineering Ecosystem](https://github.com/EmaanHumayun/backend-engineering-hub)** maintained by Emaan Humayun (**Software Engineer | DevOps Engineer**).

---

## Ecosystem Navigation

- [Central Architecture Hub](https://github.com/EmaanHumayun/backend-engineering-hub)
- [Level 1: Beginner Projects](https://github.com/EmaanHumayun/backend-beginner-projects)
- [Level 2: Intermediate Projects](https://github.com/EmaanHumayun/backend-intermediate-projects)
- [Level 3: Advanced Projects](https://github.com/EmaanHumayun/backend-advanced-projects)
- [Level 4: Professional Projects](https://github.com/EmaanHumayun/backend-professional-projects)

---

## Projects in this Repository

| Project ID | Project Name | Primary Stack | Core Concepts | Status |
| :---: | :--- | :--- | :--- | :--- |
| **11** | [**Modular Monolithic SaaS Backend**](./projects/11-modular-monolithic-saas-backend/) | TypeScript, Node.js, PostgreSQL | Modular architecture, repository pattern, multi-tenancy, subscription logic | `Ready for Practice` |
| **12** | [**Advanced API Gateway**](./projects/12-advanced-api-gateway/) | Node.js, Express, Redis | Reverse proxy, centralized authentication, rate limiting, dynamic routing, versioning | `Ready for Practice` |
| **13** | [**Real-Time Chat Backend**](./projects/13-real-time-chat-backend/) | Node.js, Socket.IO, Redis | WebSockets, rooms, user presence, message persistence, receipts, reconnection | `Ready for Practice` |
| **14** | [**Advanced Search and Analytics API**](./projects/14-advanced-search-analytics-api/) | Node.js, PostgreSQL, Redis | Full-text search, Redis caching, cache invalidation, aggregation, performance profiling | `Ready for Practice` |
| **15** | [**Backend Testing and Security Platform**](./projects/15-backend-testing-security-platform/) | TypeScript, Vitest, Supertest | Unit & integration testing, OWASP API Top 10 security, input sanitization, load testing | `Ready for Practice` |

---

## Standard Project Layout

Every project under `projects/` is organized with clean separation of concerns:

```text
[project-name]/
├── README.md                   # Project overview, installation & API guide
├── PROJECT-SPECIFICATION.md     # 20-point comprehensive engineering specification
├── REQUIREMENTS.md             # Functional and non-functional requirements
├── CHANGELOG.md                # Project version history
├── .env.example                # Configuration parameters template
├── docs/                       # Architecture, API routes & database schemas
├── src/                        # Controllers, services, models, routes, middleware
├── tests/                      # Unit and integration test suites
├── database/                   # Migrations and seed data
└── deployment/                 # Dockerfile and docker-compose.yml
```
