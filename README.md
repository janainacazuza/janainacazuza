<div align="center">

```
┌─────────────────────────────────────────────────────────┐
│  JANAÍNA CAZUZA                                         │
│  Software Engineer   ::   Java Platform & Backend       │
└─────────────────────────────────────────────────────────┘
```

[![Java](https://img.shields.io/badge/Java_21|25-ED8B00?style=flat-square&logo=openjdk&logoColor=white)](https://openjdk.org/)
[![Spring Boot](https://img.shields.io/badge/Spring_Boot_3.x-6DB33F?style=flat-square&logo=springboot&logoColor=white)](https://spring.io/projects/spring-boot)
[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)](https://www.postgresql.org/)
[![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)](https://www.docker.com/)
[![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)](https://www.kernel.org/)

</div>

---

## About

Backend Software Engineer with a focus on **correctness, clarity, and long-term maintainability** of systems built on the Java platform.

My approach to engineering starts from the fundamentals: understanding **data structures, algorithms, and computational trade offs** not as knowledge to be recited, but as lenses through which every design decision is examined. A well-chosen structure or a clearly scoped abstraction prevents entire categories of problems before they arise.

I track the **Java platform from version 21 through 25** closely: the concurrency model introduced by Project Loom, the expressiveness gains from records and sealed types, and the ongoing work of Project Valhalla on value semantics. These are not features to collect; they are tools that change how problems can be reasoned about.

> _"Good software is not the result of clever code. It is the result of clear thinking applied consistently."_

---

## Core Competencies

### Java Platform

| Area | Detail |
|---|---|
| **Type System** | Records, sealed classes, pattern matching for switch, exhaustive modeling of domain states |
| **Concurrency Model** | Virtual Threads (Project Loom), Structured Concurrency, understanding of thread safety boundaries |
| **Java 25 Preview** | Value classes (Project Valhalla), unnamed patterns and variables, string templates |
| **JVM Behavior** | Memory model, garbage collection (G1, ZGC), class loading and runtime compilation basics |
| **Standard Library** | Collections framework, Stream API, Optional, and functional interface composition |

### Algorithms & Data Structures

| Area | Detail |
|---|---|
| **Fundamental Structures** | Arrays, linked lists, trees (BST, AVL), hash tables, heaps, graphs |
| **Problem Solving Strategies** | Divide and conquer, dynamic programming, greedy approaches, backtracking |
| **Complexity Reasoning** | Evaluating time and space complexity as part of every implementation decision |
| **Ordering & Retrieval** | Sorting algorithms, binary search and its application in real backend scenarios |

### Backend & Persistence

| Area | Detail |
|---|---|
| **Spring Boot 3.x** | Application layering, dependency injection, lifecycle and transaction management |
| **Spring Data JPA** | Repository design, fetch strategy control, N+1 identification and resolution |
| **PostgreSQL** | Relational schema design, index strategy, query analysis, transactional integrity |
| **REST API Design** | Resource modeling, error contracts, versioning and documentation practices |

---

## Selected Projects

### Domain Modeling with Java 21 Sealed Types and Pattern Matching

**Context:** Representing complex business states in a backend service without relying on unchecked conditionals or fragile inheritance hierarchies.

**Engineering decisions:**

Designed the domain model using **sealed interfaces and records** to enforce exhaustive state representation at compile time. Applied **pattern matching for switch** to replace brittle instance of chains with expressive, type-safe dispatch. Validated the design using unit tests that verified each state transition explicitly, treating the type system as a first line of correctness.

**Outcome:** A domain layer where invalid states are unrepresentable and business logic reads as a direct expression of the problem, not an artifact of the implementation language.

---

### Persistence Layer with Spring Boot 3 and PostgreSQL

**Context:** Building a data layer that remains consistent and observable as the application grows in complexity and load.

**Engineering decisions:**

Structured the persistence layer around clear transactional boundaries, ensuring that each operation either completes fully or leaves the system in a known state. Resolved **N+1 query problems** through deliberate fetch strategy configuration and query consolidation. Applied index analysis to guarantee that query performance does not degrade silently as data volume increases.

**Outcome:** A persistence layer that behaves predictably under load and is straightforward to reason about during maintenance and evolution.

---

## Technology Radar

```
Adopted        →  Java 21+, Spring Boot 3, PostgreSQL, Git, Docker
Experimenting  →  Java 25 preview features (Valhalla), Testcontainers, Structured Concurrency APIs
Watching       →  GraalVM Native Image, Project Panama, OpenTelemetry for JVM
```

---

## Connect

<div align="center">

| | |
|---|---|
| 💼 LinkedIn | [linkedin.com/in/janainacazuza](https://linkedin.com/in/janainacazuza) |
| 📬 Email | [janainacazuza@proton.me](mailto:janainacazuza@proton.me) |

_Open to backend engineering roles where correctness and code quality are taken seriously._

</div>

---

<div align="center">
<sub>Clarity in design. Precision in execution.</sub>
</div>
