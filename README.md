# Dockerized Nginx Website

## Project Overview

This project demonstrates how to deploy a static website using Docker and Nginx. It shows how to containerize a simple HTML application and run it inside a Docker container.

---

## Tech Stack

* Docker
* Nginx
* HTML

---

## How It Works

* A custom Docker image is built using a Dockerfile
* Nginx is used as the web server
* The container serves the website on a mapped port

---

## Run Locally

### Build Docker Image

```
docker build -t farsana-site .
```

### Run Container

```
docker run -d -p 8081:80 --name farsana-app farsana-site
```

### Access Application

Open in your browser:

```
http://localhost:8081
```

---

## Output

Displays a custom webpage:
**Hello from Farsana **

---

## Docker Hub

https://hub.docker.com/r/farsanaks/farsana-site

---

## Key Learnings

* Built a custom Docker image using Dockerfile
* Deployed a containerized web application
* Understood port mapping and container lifecycle
* Gained hands-on experience with Docker commands

---

## Future Improvements

* Add Docker Compose for multi-container setup
* Implement CI/CD pipeline using GitHub Actions
* Deploy the application on AWS

---

