# PSUSphere Docker Deployment

This repository contains the Docker configuration for the PSUSphere Django application.

## Requirements

- Docker Desktop
- Docker Compose
- Internet connection

## Project Files

- `Dockerfile` - Defines the Django application image.
- `docker-compose.yml` - Builds and runs the application locally.
- `requirements.txt` - Lists the Python dependencies.
- `.dockerignore` - Excludes unnecessary files from the Docker build.
- `for_client/docker-compose.yml` - Pulls and runs the published Docker Hub image.

## Build and Run Locally

Run this command in the project directory:

```bash
docker compose up --build