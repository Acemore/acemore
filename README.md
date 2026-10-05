# Hi there, I'm Sergey Martynov (Acemore) 👋

An engineer with a foundational degree in Applied Mathematics and Computer Science. I specialize in building asynchronous Python backend systems, optimizing relational database architectures, and establishing declarative server infrastructure (DevOps).

## 🛠️ Main Tech Stack

* **Languages:** Python (Async Stack), C# / .NET (OOP architecture, code review & refactoring).
* **Backend:** FastAPI, Asyncio, SQLAlchemy 2.0 (Async / Mapped), Pydantic v2, APScheduler.
* **Databases & Migrations:** PostgreSQL (async connection pool management, transactional rollbacks), Alembic.
* **DevOps:** Docker, Docker Compose (multi-container orchestration, services dependency tuning), GitHub Actions (CI / CD pipelines), uv, Git (Conventional Commits), Linux / Bash.
* **QA & Observability:** Pytest (AsyncMock, database test isolation), Mypy, Ruff, structlog (structured JSON logging).
* **Data Layer & Network:** httpx (asynchronous HTTP clients), selectolax (high-performance DOM parsing).

---

## 📈 Key Featured Project

### 🚀 [JobRadar](https://github.com/Acemore/job-radar-backend)
An isolated, high-performance asynchronous ETL system for stream processing, unification, and analysis of data from heterogeneous external web sources.

* **High Availability Architecture:** Designed a dynamic Network Routing Layer with a Round-Robin load balancer and async error boundaries to ensure non-blocking pipeline execution under heavy load.
* **Asynchronous Pipeline Core:** Built a Clean Architecture processing engine using FastAPI and SQLAlchemy 2.0, utilizing atomicity hooks (`INSERT ... ON CONFLICT DO NOTHING`) at the PostgreSQL engine level to achieve high memory efficiency.
* **Containerized Infrastructure:** Configured isolated multi-container environments and automated local service infrastructures using Docker and Docker Compose.
* **Efficient Data Workers:** Implemented Alembic versioning, non-blocking background exports (CSV / Excel) offloaded to `asyncio.to_thread` pools.
* **Production-Grade QA & CI / CD:** Developed strict GitHub Actions automation integrating type checking (`Mypy`), fast linting (`Ruff`), transaction-isolated network mock testing with `Pytest`, and project Docker image building.

---

## 📬 Connect with me

* **Email:** acemore007@gmail.com
* **Habr Career:** [https://career.habr.com/acemore](https://career.habr.com/acemore)
