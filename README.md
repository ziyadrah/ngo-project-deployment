# ngo-project-deployment

## 📦 Project Name

**A full-stack application with a FastAPI backend and Vite + React frontend.**  
Built with Docker, deployed via GitHub Actions, and structured for scalable development and deployment.

## 🛠️ Technologies

- **Backend**: FastAPI, SQLAlchemy, Alembic
- **Frontend**: Vite, React
- **CI/CD**: GitHub Actions
- **Containerization**: Docker
- **Database**: MySQL
- **ORM**: SQLAlchemy
- **Authentication**: OAuth2 with JWT
- **Secrets Management**: GitHub Secrets
- **Web Server**: Nginx (optional for future production)
- **Testing**: Pytest for backend, Vitest for frontend
- **Linting**: Flake8 for backend, ESLint for frontend
- **Version Control**: Git, GitHub
- **Environment Management**: Docker Compose for local development

## 🚀 Features

- 🔒 Submodules for frontend and backend
- ✅ CI/CD with linting, testing and building
- 🐳 Dockerized services using Docker
- 🔐 Secrets managed with GitHub Actions
- 🌐 Optional Nginx + HTTPS setup for future production

## ⚙️ Setup Instructions

### Clone the repo with submodules

```bash
git clone --recurse-submodules https://github.com/ziyadrah/ngo-project-deployment.git
cd ngo-project-deployment
```

### Build and run the Docker containers

```bash
docker-compose up --build
```

### Run the backend migrations

```bash
docker-compose exec backend alembic upgrade head
```

### Access the application

- **Backend**: [http://localhost:8000](http://localhost:8000)
  
- **Frontend**: [http://localhost:3000](http://localhost:3000)

## 📦 Docker Images

- [Backend Docker Image](https://hub.docker.com/r/bouzalmat/back)

- [Frontend Docker Image](https://hub.docker.com/r/abdooch/front)

## Team

- [Abdellah Chentouf](mailto:chentouf.abdellah@ensi.ma)

- [Karima Bouzalmat](mailto:bouzalmat.karima@ensi.ma)

- [Ziyad Benhdouba](mailto:benhdouba.ziyad@ensi.ma)