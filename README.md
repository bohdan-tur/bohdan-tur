<h1 align="center">Bohdan Turevych</h1>

<p align="center">
  <strong>Junior Python Backend Developer</strong><br>
  FastAPI · Django · PostgreSQL · Redis · Celery
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/bohdan-turevych">
    <img src="https://img.shields.io/badge/LinkedIn-Bohdan%20Turevych-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn">
  </a>
  <a href="https://mail.google.com/mail/?view=cm&fs=1&to=turevicbogdan4@gmail.com">
    <img src="https://img.shields.io/badge/Email-Contact%20me-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email">
  </a>
  <img src="https://img.shields.io/badge/Open%20to-Remote%20Junior%20Backend%20Roles-2EA44F?style=flat-square" alt="Open to remote junior backend roles">
</p>

## About me

I am a Python backend developer focused on building reliable REST APIs, background
processing systems, and database-driven applications with FastAPI and Django.

I enjoy turning unclear requirements into small, verifiable engineering tasks and taking
ownership of a feature from implementation to testing and documentation.

I value clear communication, constructive feedback, and reliable teamwork. I am
comfortable working independently in a remote environment while keeping my progress
and technical decisions visible to the team.

## Featured projects

### [Price Tracker](https://github.com/bohdan-tur/price-tracker) — FastAPI, scraping and Telegram automation

[![Price Tracker CI](https://img.shields.io/github/actions/workflow/status/bohdan-tur/price-tracker/ci.yml?branch=main&style=flat-square&logo=githubactions&logoColor=white&label=Price%20Tracker%20CI)](https://github.com/bohdan-tur/price-tracker/actions/workflows/ci.yml)
![Coverage](https://img.shields.io/badge/Coverage-78%25-green?style=flat-square)

Asynchronous price-monitoring backend that scrapes product pages, records price
history, and delivers Telegram notifications when configured conditions are met.

- Built REST APIs with FastAPI, SQLAlchemy, PostgreSQL, and Pydantic.
- Implemented Celery workflows for scraping, price checks, and Telegram delivery.
- Added bounded retries, idempotent task processing, rate limiting, and SSRF protection.
- Added Prometheus metrics and a Grafana dashboard for HTTP and Celery monitoring.
- Verified a local observability run with **1,162 requests in 30 seconds**, **0 failures**, and **95 ms HTTP p95 latency**.

### [BudgetFlow API](https://github.com/bohdan-tur/budgetflow-api) — Django REST Framework

[![BudgetFlow CI](https://img.shields.io/github/actions/workflow/status/bohdan-tur/budgetflow-api/ci.yaml?branch=main&style=flat-square&logo=githubactions&logoColor=white&label=BudgetFlow%20CI)](https://github.com/bohdan-tur/budgetflow-api/actions/workflows/ci.yaml)
![Coverage](https://img.shields.io/badge/Coverage-92%25-brightgreen?style=flat-square)

Personal-finance REST API for managing accounts, categories, transactions, budgets,
recurring operations, and financial summaries.

- Implemented token-based authentication, permission boundaries, filtering, and pagination.
- Used database transactions and row-level locking for consistent financial operations.
- Added recurring transaction processing with Celery and Redis.
- Maintained **135 automated tests**, **92% coverage**, and an **85% CI coverage threshold**.

### [Booking API](https://github.com/bohdan-tur/booking-app) — FastAPI

[![Booking API CI](https://img.shields.io/github/actions/workflow/status/bohdan-tur/booking-app/ci.yaml?branch=main&style=flat-square&logo=githubactions&logoColor=white&label=Booking%20API%20CI)](https://github.com/bohdan-tur/booking-app/actions/workflows/ci.yaml)
![Coverage](https://img.shields.io/badge/Coverage-78%25-green?style=flat-square)

Hotel-booking REST API with authentication, availability checks, reservations,
payments, reviews, and administrative operations.

- Implemented JWT access and refresh tokens with rotation and Argon2 password hashing.
- Protected booking operations from race conditions with transactional consistency controls.
- Added role-based authorization, rate limiting, health checks, and structured error handling.
- Maintained **139 automated tests** with **78% code coverage**.

## Tech stack

### Backend

![Python](https://img.shields.io/badge/Python-3.12%20%7C%203.13-3776AB?style=for-the-badge&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white)
![DRF](https://img.shields.io/badge/DRF-A30000?style=for-the-badge&logo=django&logoColor=white)
![Pydantic](https://img.shields.io/badge/Pydantic-E92063?style=for-the-badge&logo=pydantic&logoColor=white)

### Databases and background processing

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?style=for-the-badge&logo=sqlalchemy&logoColor=white)
![Celery](https://img.shields.io/badge/Celery-37814A?style=for-the-badge&logo=celery&logoColor=white)
![Alembic](https://img.shields.io/badge/Alembic-Migrations-6BA81E?style=for-the-badge)

### Testing and code quality

![Pytest](https://img.shields.io/badge/Pytest-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white)
![Ruff](https://img.shields.io/badge/Ruff-D7FF64?style=for-the-badge&logo=ruff&logoColor=261230)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)

### Infrastructure and observability

![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Docker Compose](https://img.shields.io/badge/Docker%20Compose-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white)
![Flower](https://img.shields.io/badge/Flower-Celery%20Monitoring-37814A?style=for-the-badge)

### Familiar with

![AWS Fundamentals](https://img.shields.io/badge/AWS-Fundamentals-FF9900?style=for-the-badge&logo=amazonwebservices&logoColor=232F3E)

## GitHub statistics

<p align="center">
  <a href="https://github.com/bohdan-tur">
    <img
      width="650"
      src="https://github-stats-extended.vercel.app/api?username=bohdan-tur&show_icons=true&include_all_commits=true&rank_icon=github&theme=github_dark&hide_border=true&custom_title=GitHub%20Stats"
      alt="GitHub statistics"
    >
  </a>
</p>

<p align="center">
  <a href="https://github.com/bohdan-tur">
    <img
      width="450"
      src="https://github-stats-extended.vercel.app/api/top-langs?username=bohdan-tur&layout=compact&langs_count=6&theme=github_dark&hide_border=true&custom_title=Most%20Used%20Languages"
      alt="Most used languages"
    >
  </a>
</p>

## Engineering focus

- Transactional consistency and concurrency control.
- Secure authentication and authorization boundaries.
- Background jobs with bounded retries and idempotent processing.
- Defensive integrations with external services.
- Automated testing, CI checks, and maintainable documentation.
- Application metrics and practical observability.

## Education

**BSc in Software Engineering**  
Lviv Polytechnic National University · Expected graduation: 2029

## Contact

I am open to **remote Junior Python Backend Developer** opportunities involving
FastAPI, Django, REST APIs, PostgreSQL, automation, scraping, or Telegram integrations.

Feel free to reach out via LinkedIn or email above.
