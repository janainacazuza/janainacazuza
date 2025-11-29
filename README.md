# Janaína Cazuza | Systems Performance Engineer (In Transition)

### From Critical Care Medicine to Critical Data Systems.

I don't just move data; I engineer the cost and latency of every byte.
Transitioning from Medicine to High-Performance Data Engineering with a focus on **Streaming Systems**, **Low-Level Optimization**, and **Infrastructure Cost Efficiency**.

My background in critical care medicine trained me to diagnose complex systems under pressure. Today, I apply that same diagnostic rigor to distributed systems, focusing on observability, fault tolerance, and "physics-first" engineering.

---

###  Engineering Philosophy: "Logic First, Metric Second"

I believe modern abstractions often hide incompetence. My work focuses on understanding the underlying mechanics (OS, Memory, Network) to build systems that are not just functional, but efficient and predictable.

* **Audit-Driven Development:** If it can't be measured (CPU cycles, I/O wait, Latency), it doesn't exist.
* **Infrastructure as Code:** ClickOps is forbidden. Everything is reproducible via Terraform/Docker.
* **Foundations over Frameworks:** Mastery of C and Linux Internals to better optimize high-level Python/Java pipelines.

---

###  Core Stack & Learning Track

| Domain | Tooling & Concepts |
| :--- | :--- |
| **Low-Level Foundations** | **C** (Memory Management), **Linux Internals** (Syscalls, Processes), **Networking** (TCP/IP tuning) |
| **Data Engineering** | **Python** (Pandas/PyArrow - Vectorized Execution), **SQL** (Postgres Query Planning) |
| **Containerization** | **Docker** (Multi-stage builds, Distroless images), **ECS/Fargate** |
| **Orchestration** | **Apache Airflow** (Custom Operators) |
| **Infra as Code** | **Terraform** (Modular Architecture) |

---

###  Featured Engineering Asset: [Data Engineering Journey](https://github.com/janainacazuza/data-engineering-journey)

*Note: This is not a tutorial repo. This is an Engineering Logbook documenting the build of a production-grade Data Platform from scratch.*

**Current Sprint Status:** `v0.1 Delivered` (Dockerized Ingestion Pipeline)

**The Engineering Challenge:**
Ingest high-frequency data from public APIs while minimizing storage footprint and ensuring reproducibility across environments (Local vs Cloud).

**Key Implementations:**
* **Storage Optimization:** Implemented a columnar storage strategy (**Parquet + Snappy**), achieving **~48% reduction** in file size compared to standard JSON row-based storage.
* **Containerization:** Full isolation using Docker (Debian Slim base) with non-root user security.
* **Reliability:** Centralized configuration management and rigid type-hinting (mypy) for compile-time safety in Python.

 **[View Code & Architecture](https://github.com/janainacazuza/data-engineering-journey)**

---

### Long-Term Project: [Asymptora - Data Platform](https://github.com/janainacazuza/aws-data-platform-asymptora)
*(Under Construction)*
Designing an end-to-end cloud data platform with strict SLOs (Service Level Objectives) for availability and throughput.

---

###  Contact

**[LinkedIn](https://www.linkedin.com/in/janainacazuza/)** | 
