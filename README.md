# docker-python-ci-starter

Simple Python (Flask) application containerized with Docker and validated using GitHub Actions CI.

## Features
- Dockerized Python application
- GitHub Actions CI pipeline
- Automated container build and health check

## Local run
```bash
docker build -t python-ci-app .
docker run -p 5000:5000 python-ci-app