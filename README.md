<h1 align="center">Bohdan Turevych</h1>

<p align="center">
  <strong>Python Backend Developer · FastAPI · Django</strong>
</p>

<p align="center">
  Software Engineering student at Lviv Polytechnic National University.<br>
  I build tested backend systems with asynchronous APIs, transactional business
  logic, background processing, and practical observability.
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/bohdan-turevych"><img src="https://img.shields.io/badge/LinkedIn-Bohdan%20Turevych-0A66C2?logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:turevicbogdan4@gmail.com"><img src="https://img.shields.io/badge/Email-turevicbogdan4%40gmail.com-EA4335?logo=gmail&logoColor=white" alt="Email"></a>
  <img src="https://img.shields.io/badge/Open%20to-Remote%20Junior%20Backend%20Roles-2EA44F" alt="Open to remote junior backend roles">
</p>

## Selected projects

### [Price Tracker](https://github.com/bohdan-tur/price-tracker) — FastAPI, scraping, Telegram

An asynchronous price-monitoring backend that tracks products, stores price
history, and sends target-price alerts through Telegram.

- Celery and Redis handle scheduled checks, isolated retries, and notification delivery.
- The scraper defends against SSRF through allowlists, DNS checks, redirect validation, and response-size limits.
- Prometheus, Grafana, and Flower expose HTTP and Celery behavior.
- A controlled local run processed **1,162 requests in 30 seconds** with **0 failures** and **95 ms HTTP p95 latency**.

### [BudgetFlow API](https://github.com/bohdan-tur/budgetflow-api) — Django REST Framework

A personal-finance API for wallets, transactions, transfers, budgets, and
currency-aware reports.

- Financial operations use Decimal, atomic transactions, and row-level locks.
- User-scoped querysets prevent cross-account access to financial data.
- Same-currency transfers and balance changes enforce explicit business rules.
- **135 tests** cover authentication, balances, insufficient funds, isolation, budgets, and reports; CI enforces **85%+ coverage**.

### [Booking API](https://github.com/bohdan-tur/booking-app) — FastAPI, concurrency

A capacity-aware hotel-booking backend with secure authentication and scheduled
background workflows.

- PostgreSQL SELECT ... FOR UPDATE protects inventory under concurrent booking attempts.
- Rotating refresh tokens are stored as hashes and guarded against concurrent reuse.
- Role-based access separates user, manager, and administrator operations.
- **139 tests** cover security, booking lifecycle, Celery behavior, and real PostgreSQL race conditions.

## Core stack

| Area | Technologies |
|---|---|
| Backend | Python, FastAPI, Django, Django REST Framework, Pydantic |
| Data | PostgreSQL, SQLAlchemy, Django ORM, Alembic, Redis |
| Async and integrations | Celery, Celery Beat, HTTPX, Beautiful Soup, aiogram |
| Security | JWT, Argon2, RBAC, rate limiting, SSRF defenses |
| Testing | Pytest, pytest-asyncio, pytest-django, HTTPX, Factory Boy, coverage.py |
| Infrastructure | Docker, Docker Compose, GitHub Actions |
| Observability | Prometheus, Grafana, Flower |

## Engineering focus

- Transactional consistency and concurrency control.
- Secure authentication and authorization boundaries.
- Background jobs with bounded retries and idempotent processing.
- Reproducible environments, migrations, automated tests, and CI.
- Clear API contracts and operational visibility.

## Education and achievements

- **BSc in Software Engineering**, Lviv Polytechnic National University — expected 2029.
- **Presidential Scholarship, 2025** — awarded for NMT results of 185+.
- **BEST::HACKath0n 2026 participant** — team backend development; certificate of participation.

## Contact

I am open to **remote Junior Python Backend Developer** opportunities involving
FastAPI, Django, REST APIs, PostgreSQL, automation, scraping, or Telegram
integrations.

- LinkedIn: [linkedin.com/in/bohdan-turevych](https://www.linkedin.com/in/bohdan-turevych)
- Email: [turevicbogdan4@gmail.com](mailto:turevicbogdan4@gmail.com)
