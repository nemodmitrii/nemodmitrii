# Dmitrii Gusev

**Senior Java Software Engineer** · 7+ years experience · Open to relocation

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/nemo-gusev-dmitrii)
[![Email](https://img.shields.io/badge/Email-dmitrii.s.gusev%40gmail.com-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:dmitrii.s.gusev@gmail.com)

## About

Java Software Engineer with 7+ years of experience in the nuclear industry, industrial maintenance, and healthcare. I specialize in the Spring ecosystem, distributed systems, event-driven architecture, and security.

I have worked across the full development lifecycle:

- turning client requests into technical specifications
- designing microservice and database architecture
- implementing features across the database, backend, and UI layers
- covering services with tests and monitoring
- building CI/CD pipelines and administering dev/QA servers

## Tech Stack

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat&logo=kotlin&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat&logo=springboot&logoColor=white)
![Hibernate](https://img.shields.io/badge/Hibernate-59666C?style=flat&logo=hibernate&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white)
![Apache Kafka](https://img.shields.io/badge/Apache_Kafka-231F20?style=flat&logo=apachekafka&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=flat&logo=rabbitmq&logoColor=white)
![Keycloak](https://img.shields.io/badge/Keycloak-4D4D4D?style=flat&logo=keycloak&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat&logo=kubernetes&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat&logo=grafana&logoColor=white)

<details>
<summary><b>Full stack</b></summary>

| Area | Technologies |
|---|---|
| **Backend** | Java 8/11/17/21, Kotlin, Spring Boot, Spring Data, Spring MVC, Spring Security, Spring WebFlux, Spring Cloud, Spring Batch, JPA, Hibernate, jOOQ, Reactor Netty, OpenAPI/Swagger |
| **Testing** | JUnit, Mockito, MockMvc, WireMock |
| **Security** | OAuth2, JWT, Keycloak, AD + Kerberos, LDAP |
| **Data & Messaging** | SQL, PostgreSQL, Oracle, H2, Redis, MongoDB, OpenSearch, BigQuery; PL/SQL, JDBC, R2DBC, Flyway, Liquibase; Apache Kafka, RabbitMQ |
| **Cloud & DevOps** | Jenkins, Maven, Gradle, Git, Tomcat; Docker, Docker Swarm, Kubernetes, Helm; Prometheus, Grafana; AWS (S3), GCP, MinIO |
| **Architecture & Practices** | Microservices, API Gateway, Event-Driven Architecture, REST APIs, SOAP, RPC, Distributed Systems, Workflow Orchestration (Conductor OSS), DDD, TDD, SOLID, design patterns; Agile, Scrum, code review |
| **Frontend** | JavaScript, TypeScript, Vue.js |

</details>

## Experience

### [Cloudaware](https://cloudaware.com/) — Java Software Engineer (Contract)
*Jun 2026 – Present*

**Multi-cloud CMDB integrations.** This internal project extends a multi-cloud CMDB platform's client-facing data integrations.

- Updated benchmark export and daily-metering data integrations for multiple clients, orchestrated via Conductor OSS workflows.
- Migrated client data-integration job pipelines from the legacy orchestration solution to Conductor OSS workflows.

`Java 21` `Conductor OSS` `BigQuery` `MongoDB` `AWS` `GCP`

### [KRIT](https://krit.global/) — Java Software Engineer
*Apr 2019 – Jun 2026 · St. Petersburg, Russia (Hybrid) / Sapporo, Japan (Remote)*

#### Rosatom Automated Emergency Prediction & Analysis System (2020–2026)
24/7 situational-awareness and prediction system for nuclear industry facilities. It runs on 8+ microservices with high-load data ingestion (radiation, meteorological, NASA).

- Carried out the backend modernization:
  - migrated from GWT to Spring + Hibernate
  - upgraded the codebase to Java 17
  - split the monolith into frontend and backend services
  - integrated Apache Kafka for radiation monitoring data pipelines
- Set up CI/CD with Jenkins, Docker, and Docker Swarm.
- Achieved a **~5× speedup** on Information Reference System operations by moving heavily nested DB-resident logic into the backend layer.
- Increased test coverage from **36% to 92%**.
- Set up Prometheus/Grafana observability covering JVM metrics and SLAs.
- Built bulk messaging services from scratch for emergency and scheduled notifications via email, SMS, and ViPNet.
- Built cluster architecture support with HAProxy, ZooKeeper, and Redis for high availability and fault tolerance.

#### [KRITical Maitenance](https://krit.global/solutions/kritical-maintenance/) (2024–2026)
An equipment inspection, orders, and repair scheduling system for industrial facilities, built on ~15 microservices.

- Introduced a unified API Gateway as the centralized entry point for clients.
- Designed a role-based access model with permission updates propagated across services via a RabbitMQ event bus.
- Accelerated registry data loading by **~50%** through query and indexing optimizations.
- Combined Java 21 and Kotlin microservices within a single architecture.

#### Nordgold maintenance & repair system (2025–2026)
An enterprise maintenance platform integrated with SAP, built on ~20 microservices.

- Delivered new SAP integration modules and scaled existing ones for increased data volumes.
- Accelerated KPI calculations by up to **36%** and reduced their memory footprint by up to **22%**.
- Accelerated data loading from SAP integrations by **~30%**.

#### Medscan Hadassah patient portal (2025)
A mobile and web application for a medical center's patient services, built on ~7 microservices.

- Implemented the IAM/account service as the unified entry point, plus the API gateway.
- Implemented an OAuth2 authorization flow with code/captcha verification.
- Integrated Keycloak and Active Directory for identity and access management.

## Education

**Bachelor of Engineering, Informatics and Computer Engineering**, Pskov State University (2013–2017, Honors Diploma)

## Languages

Russian (native) · English (professional working proficiency) · Japanese (JLPT N4, certified Dec 2024)
