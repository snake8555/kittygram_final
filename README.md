# Kittygram

Kittygram is a web application where users can create profiles for their cats, upload photos, and share information about their pets.

The project includes a Django REST API, React frontend, Docker containerization, Nginx, and automated CI/CD with GitHub Actions.

## Tech Stack

- Python
- Django
- Django REST Framework
- React
- Docker
- Docker Compose
- Nginx
- GitHub Actions
- pytest

## Features

- User authentication
- Create and manage cat profiles
- Upload cat photos
- REST API
- Containerized deployment
- Automated testing and deployment with GitHub Actions

## Running the Project

Clone the repository and create a `.env` file based on `.env.example`.

```bash
docker compose up -d --build
```

For production:

```bash
docker compose -f docker-compose.production.yml up -d
```

## Testing

```bash
pip install -r backend/requirements.txt
pytest
```

## Author

Vladimir Zhurov
