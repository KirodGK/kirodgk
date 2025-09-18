# 👨‍💻 Привет! Я — Python-разработчик

> Бэкенд-инженер с опытом построения масштабируемых, отказоустойчивых систем с использованием современных технологий.

---

## 🛠️ Технологический стек

![Python](https://img.shields.io/badge/Python-3.12-blue?logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-0.110-black?logo=fastapi&logoColor=white)
![Django](https://img.shields.io/badge/Django-4.2-green?logo=django&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-15-blue?logo=postgresql&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-2.0-yellow?logo=sqlalchemy&logoColor=black)
![Celery](https://img.shields.io/badge/Celery-tasks-green?logo=celery&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-persistence-red?logo=redis&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-message--broker-orange?logo=rabbitmq&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-monitoring-red?logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-visualization-orange?logo=grafana&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-containerization-blue?logo=docker&logoColor=white)


---

## 💼 Что я умею

✅ Разработка RESTful API на **FastAPI**  
✅ Создание админ-панелей и сложной бизнес-логики на **Django**  
✅ Работа с **PostgreSQL**: индексы, транзакции, оптимизация запросов  
✅ ORM: **SQLAlchemy** (в FastAPI) и **Django ORM**  
✅ Асинхронная обработка задач через **Celery + RabbitMQ / Redis**  
✅ Кэширование данных и сессий с помощью **Redis**  
✅ Построение микросервисной архитектуры  
✅ Мониторинг и метрики: **Prometheus + Grafana**  
✅ Автоматическая документация (Swagger/OpenAPI)  
✅ CI/CD, Docker, контейнеризация сервисов  

---

## 📊 Мониторинг и производительность

Я убеждён, что хороший сервис — это не только работающий код, но и:
- Видимость в реальном времени (логи, метрики)
- Уведомления о проблемах
- Профилирование производительности

🛠 Использую:
- **Prometheus** для сбора метрик (CPU, память, количество запросов, время ответа)
- **Grafana** для дашбордов
- Кастомные метрики в FastAPI и Django

---

## 🐳 Инфраструктура

Все сервисы запускаются в контейнерах:

```yaml
# docker-compose.yml (пример)
services:
  web-api:
    build: ./api
    ports:
      - "8000:8000"
  celery-worker:
    build: ./worker
    environment:
      - BROKER_URL=redis://redis:6379/0
  redis:
    image: redis:7-alpine
  rabbitmq:
    image: rabbitmq:3-management
  prometheus:
    image: prom/prometheus
  grafana:
    image: grafana/grafana
```

## 🌐 Связь со мной

Можете связаться со мной через любую из платформ ниже:

- 📬 **Email**: [KirodGK@gmail.com](mailto:KirodGK@gmail.com)
- 🐙 **GitHub**: [@KirodGK](https://github.com/KirodGK)
- 📞 **Telegram**: [@KirodGK_2_0](https://t.me/KirodGK_2_0)
