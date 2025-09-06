# The Movie Rater (temp name)

The Movie Rater is a learning project designed to showcase a modern, scalable backend architecture using microservices. This application allows users to browse a collection of movies and submit their own ratings. The system is built with two independent services that communicate via a RESTful API. This project is not just a demo; it’s a foundation for a larger platform and a hands-on exploration of backend development best practices.

---

## 🚀 Core Features
- **RESTful APIs**: Full set of endpoints for managing movies and ratings.
- **Microservices Architecture**:
  - **Movies Service**: Manages movie data (title, year, etc).
  - **Ratings Service**: Manages user-submitted ratings.
- **Database Integration**: PostgreSQL for persistence. Each service has its own schema and migrations (Alembic/Flask-Migrate).
- **Inter-Service Communication**: Movies service fetches average ratings from the Ratings service.
- **Frontend Integration**: A simple HTML/CSS/JS frontend to browse movies, view average ratings, and submit new ratings.

---

## 🛠️ Additional Features (4-Week Scope)
- **Dockerization**: Each service containerized, orchestrated with `docker-compose`.
- **Basic Authentication Stub**: API key or dummy user to secure rating endpoints.
- **Unit Testing**: `pytest` coverage for movies and ratings endpoints.
- **Frontend QoL**: Submit ratings via form, display average ratings dynamically.
- **Redis Caching**: Cache average ratings for performance.
- **Pagination**: Return paginated results when browsing movies.

---

## 📦 Tech Stack
- **Backend**: Python, Flask/FastAPI (TBD)
- **Database**: PostgreSQL
- **Migrations**: Alembic / Flask-Migrate
- **Caching**: Redis
- **Frontend**: Vanilla JS, HTML, CSS
- **Containerization**: Docker, docker-compose
- **Testing**: pytest
- **CI/CD**: GitHub Actions (linting + tests)

---

## 📅 Roadmap
- **Stage 1 (MVP)**: Movies service, Ratings service, PostgreSQL, REST APIs.
- **Stage 2**: Inter-service communication, simple frontend integration.
- **Stage 3**: Dockerization, migrations, unit testing, basic auth.
- **Stage 4**: Redis caching, pagination.
- **Stage 5 (Future Scaling)**:
  - JWT authentication
  - API gateway (NGINX/Traefik)
  - gRPC inter-service communication
  - Kubernetes deployment
  - Advanced frontend (React/Vue)
  - Observability (Prometheus, Grafana)

---

## 🤝 Contributing
This project is open-source and welcomes contributions. Check the roadmap and issues for areas to explore.

---

## 📜 License
MIT License
