# Dockerized Static Website using Nginx

## Overview

This is a simple project where I containerized a static HTML website using Docker and Nginx. I built this as part of my DevOps learning to understand how Docker images and containers work in real scenarios.

---

## Technologies Used

* Docker
* Nginx
* HTML

---

## What I Did

* Created a basic static website using HTML
* Wrote a Dockerfile to build a custom image
* Used Nginx to serve the website inside a container
* Ran the container with port mapping to access it locally

---

## Project Structure

```
.
├── Dockerfile
└── index.html
```

---

## How to Run

### 1. Clone the repository

```
git clone https://github.com/Farsanaks/docker-nginx-website.git
cd docker-nginx-website
```

### 2. Build the Docker image

```
docker build -t farsana-site .
```

### 3. Run the container

```
docker run -d -p 8081:80 --name farsana-app farsana-site
```

### 4. Open in browser

```
http://localhost:8081
```

---

## Output

A simple webpage displaying:

**Hello from Farsana 🚀**

---

## What I Learned

* Basics of Docker (images, containers, Dockerfile)
* How to containerize a simple application
* Running and managing containers
* Debugging common Docker issues

---

## Author

**Farsana K S**

---

## Future Improvements

* Add Docker Compose
* Deploy on AWS EC2
* Set up CI/CD using GitHub Actions

---

