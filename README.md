User
  ↓
Browser
  ↓
Flask Application
  ↓
Docker Container


# Dockerize Demo

A simple Flask application containerized using Docker.

## Technologies Used

- Python
- Flask
- Docker

## Build Image

```bash
docker build -t flask-app .
```

## Run Container

```bash
docker run -d -p 5000:5000 --name flask-container flask-app
```

## Access Application

http://localhost:5000
