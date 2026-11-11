<h1 align="center">Bohdan Turevych</h1>

<p align="center">
  <strong>Software Engineer · Testing &amp; Quality</strong><br>
  Pytest · FastAPI · Django REST Framework · PostgreSQL · GitHub Actions · Docker
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/bohdan-turevych">
    <img src="https://img.shields.io/badge/LinkedIn-Bohdan%20Turevych-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn">
  </a>
  <a href="mailto:turevicbogdan4@gmail.com">
    <img src="https://img.shields.io/badge/Email-Contact%20me-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email">
  </a>
  <img src="https://img.shields.io/badge/Open%20to-Internship%20%7C%20Trainee%20%7C%20Junior-2EA44F?style=flat-square" alt="Open to internship, trainee and junior roles">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.12%20%7C%203.13-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" alt="FastAPI">
  <img src="https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white" alt="Django">
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL">
  <img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white" alt="Redis">
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker">
</p>

## About me

I am a Software Engineering student at Lviv Polytechnic National University. I build REST APIs and database-driven applications in Python, and the part I care about most is how they are tested.

In my projects I write Pytest suites, concurrency tests for race conditions, and CI quality gates that catch problems before merge.

## Featured projects

### [Price Tracker](https://github.com/bohdan-tur/price-tracker) — async monitoring and Telegram alerts

[![CI](https://img.shields.io/github/actions/workflow/status/bohdan-tur/price-tracker/ci.yml?branch=main&style=flat-square&logo=githubactions&logoColor=white&label=CI)](https://github.com/bohdan-tur/price-tracker/actions/workflows/ci.yml)
![Coverage](https://img.shields.io/badge/Coverage-78%25-green?style=flat-square)

FastAPI service that tracks product prices, preserves history, and sends Telegram alerts.

- Automated tests with **78% total coverage**, run in CI on every change.
- Async SQLAlchemy, PostgreSQL, Celery, Redis, and Alembic.
- Defensive scraping with SSRF protection, redirect validation, and response-size limits.
- Prometheus, Grafana, and Flower observability.
- Controlled local run: **1,162 requests**, **0 failures**, and **95 ms HTTP p95 latency**.

### [Booking API](https://github.com/bohdan-tur/booking-app) — concurrency-safe hotel reservations

[![CI](https://img.shields.io/github/actions/workflow/status/bohdan-tur/booking-app/ci.yaml?branch=main&style=flat-square&logo=githubactions&logoColor=white&label=CI)](https://github.com/bohdan-tur/booking-app/actions/workflows/ci.yaml)
![Coverage](https://img.shields.io/badge/Coverage-78%25-green?style=flat-square)

FastAPI hotel-booking backend designed to protect reservations and sessions from race conditions.

- **139 automated tests** with **78% total coverage**.
- Concurrency tests that send simultaneous booking requests to verify double booking is prevented.
- CI pipeline: linting, dependency audit, migration checks, tests, and build.
- PostgreSQL row locking, JWT sessions with refresh-token rotation, RBAC, and rate limiting.

### [BudgetFlow API](https://github.com/bohdan-tur/budgetflow-api) — multi-currency personal finance

[![CI](https://img.shields.io/github/actions/workflow/status/bohdan-tur/budgetflow-api/ci.yaml?branch=main&style=flat-square&logo=githubactions&logoColor=white&label=CI)](https://github.com/bohdan-tur/budgetflow-api/actions/workflows/ci.yaml)
![Coverage](https://img.shields.io/badge/Coverage-92%25-brightgreen?style=flat-square)

Django REST Framework API for wallets, transactions, transfers, budgets, and financial reports.

- **135 automated tests** with **92% total coverage**.
- Decimal arithmetic and strict separation of currency totals.
- Atomic balance updates and PostgreSQL row-level locking.
- JWT authentication and user-level data isolation.

## Core stack

| Area | Technologies |
|---|---|
| Testing and quality | Pytest, Postman, Ruff, pip-audit, GitHub Actions, Cypress (learning) |
| Backend | Python, FastAPI, Django REST Framework, Pydantic |
| Data | PostgreSQL, SQLAlchemy, Django ORM, Alembic, Redis |
| Background jobs | Celery, Celery Beat |
| Infrastructure | Docker, Docker Compose |
| Observability | Prometheus, Grafana, Flower |

## GitHub statistics

<p align="center">
  <img width="420" src="https://github-stats-extended.vercel.app/api?username=bohdan-tur&show_icons=true&include_all_commits=true&rank_icon=github&theme=github_dark&hide_border=true&custom_title=GitHub%20Stats" alt="GitHub statistics">
  <img width="320" src="https://github-stats-extended.vercel.app/api/top-langs?username=bohdan-tur&layout=compact&langs_count=6&theme=github_dark&hide_border=true&custom_title=Most%20Used%20Languages" alt="Most used languages">
</p>

## Engineering focus

- Test strategy: unit, integration, and API tests, including race conditions.
- CI quality gates that run on every change.
- Transactional consistency and concurrency control.
- Secure authentication and authorization boundaries.
- Defensive integrations with external services.

## Education

**BSc in Software Engineering**  
Lviv Polytechnic National University · Expected graduation: 2029

