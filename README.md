# 🐛 Abhishek Kumar — Professional Bug Creator & Occasional Bug Fixer

> *Building secure, scalable systems — one commit at a time. (And reverting them twice.)*

[![GitHub](https://img.shields.io/badge/GitHub-abhishekkumar--harman-181717?style=flat-square&logo=github)](https://github.com/abhishekkumar-harman)
[![Email](https://img.shields.io/badge/Email-abhi.go%40hotmail.com-0078D4?style=flat-square&logo=microsoft-outlook)](mailto:abhi.go@hotmail.com)
[![Location](https://img.shields.io/badge/📍_Location-Bengaluru,_India-FF6B6B?style=flat-square)]()
[![Experience](https://img.shields.io/badge/⏳_Experience-10+_Years-00C853?style=flat-square)]()

---

## 🤔 Who Even Am I? (The Elevator Pitch Nobody Asked For)

Senior Software Engineer with **10+ years** of experience designing and building scalable microservices, API gateways, and security libraries in Java. Active open-source contributor under the **Eclipse ECSP** organization with **538+ contributions** in the last year. Specializes in distributed systems architecture, JWT/OAuth2 security, and cloud-native deployments on Kubernetes.

---

## 🧰 Things I Google Less Than I Used To

| 🏷️ Category | 🔧 Technologies |
|---|---|
| **💻 Languages** | Java (17 / 21 / 25), SQL |
| **🌱 Frameworks** | Spring Boot 4.x, Spring Cloud Gateway, Spring Framework 7.x, Spring Security |
| **📨 Messaging** | Apache Kafka |
| **🗄️ Databases** | PostgreSQL, MongoDB, Redis |
| **🔐 Security** | JWT, OAuth2, JWKS, RSA/EC key management, nimbus-jose-jwt |
| **☁️ DevOps & Cloud** | Docker, Kubernetes, Helm, AWS, Jenkins, GitHub Actions, CI/CD |
| **🧪 Build & Quality** | Maven, Checkstyle, SonarCloud, JUnit 5, Mockito, Testcontainers |
| **📊 Observability** | Micrometer, Logback, SLF4J |
| **🤝 Practices** | Agile, System Design, Performance Optimization, Security Best Practices |

---

## 🔓 Code I Released Into the Wild (For Free, Like a Madman)

### 🚦 [ecsp/api-gateway](https://github.com/eclipse-ecsp/api-gateway) — The Bouncer of My Microservices Club

> A Spring Cloud Gateway-based API Gateway serving as the single entry point for microservices in the Eclipse ECSP ecosystem.

![Stars](https://img.shields.io/github/stars/eclipse-ecsp/api-gateway?style=flat-square&logo=github)
![Forks](https://img.shields.io/github/forks/eclipse-ecsp/api-gateway?style=flat-square&logo=github)
![Release](https://img.shields.io/badge/releases-54-blue?style=flat-square)
![Java](https://img.shields.io/badge/Java-21-ED8B00?style=flat-square&logo=openjdk)

- 🏗️ Architected support for **static and dynamic routing** via OpenAPI annotations stored in PostgreSQL
- 🔐 Implemented **OAuth2/JWT token validation** to authorize client requests at the gateway edge
- 📡 Built **request fan-out** — distributing a single request to multiple downstream services
- ⚡ Integrated **Redis-backed rate limiting**, circuit breakers, and response caching
- ☸️ Deployed via **Kubernetes Helm charts** (`ecsp-helm-charts`)
- 📦 **54 releases** (latest: `1.5.4`) · 3 ⭐ · 6 🍴 · 7 contributors

`Java 21` `Spring Boot 4.x` `Spring Cloud Gateway` `PostgreSQL` `MongoDB` `Redis` `Docker` `Kubernetes`

---

### 🕵️ [ecsp/token-validator](https://github.com/eclipse-ecsp/token-validator) — The JWT Police (Zero Tolerance for Bad Tokens)

> A reusable Java library for validating JWT tokens and managing public keys across microservices.

![Java](https://img.shields.io/badge/Java-25-ED8B00?style=flat-square&logo=openjdk)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-4.x-6DB33F?style=flat-square&logo=springboot)
![License](https://img.shields.io/badge/License-Apache_2.0-blue?style=flat-square)

- 🧩 Designed a **fully decomposable validation pipeline** — every stage replaceable via interfaces (parsing → algorithm → signature → claims → scope)
- 🔄 Implemented **JWKS endpoint integration** with in-memory LRU key cache, per-issuer refresh, and exponential-backoff retry
- 🛡️ Supports **RSA and EC public keys**, PEM loading, algorithm whitelisting (`alg=none` unconditionally denied)
- ⏱️ Validates `exp`, `nbf`, `iss` with configurable clock-skew tolerance; optional per-issuer `aud` validation
- ⚙️ **Spring Boot auto-configuration** with `@ConditionalOnMissingBean` overrides at every step
- 📈 Integrated **Micrometer metrics** with fully configurable `TokenValidatorMetricsConfig`
- 🔗 Currently integrating into api-gateway via [PR #258](https://github.com/eclipse-ecsp/api-gateway/pull/258)

`Java 25` `Spring Boot 4.x` `Spring Framework 7.x` `nimbus-jose-jwt` `Maven`

---

## 📉 Proof I Have No Life Outside of Commits

```
📅 Contributions (last 12 months)  ████████████████████  538+
💾 Commits                         ████████████████░░░░  82%
🔃 Pull Requests                   ██░░░░░░░░░░░░░░░░░░  11%
👀 Code Review                     █░░░░░░░░░░░░░░░░░░░   4%
🐛 Issues                          ░░░░░░░░░░░░░░░░░░░░   3%
```

🏆 **Achievements:** Pull Shark ×2 &nbsp;·&nbsp; YOLO
🌐 Contributed to **22+ repositories** across the Eclipse ECSP organization

---

## 🧓 My Origin Story (Before I Knew What I Was Getting Into)

Previously a core contributor to **[MOSIP](https://mosip.io) — Modular Open Source Identity Platform**, an open-source digital identity platform adopted by governments worldwide. Served on the **core team** responsible for creating building blocks for platform template processing (freemarker, velocity), master data management, file storage (HDFS), sync-master data and other various libraries. Contributed to the design and implementation of the **MOSIP Identity System** used in national ID programs across multiple countries.

