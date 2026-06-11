# Docker Lab

A hands-on Docker learning repository focused on understanding containerization, storage, networking, image management, orchestration, and troubleshooting through practical labs.

## Overview

This repository documents my Docker learning journey through a series of hands-on exercises. The goal was to understand how Docker works internally, how containers communicate, how data persists, and how Docker is used in real-world DevOps workflows.

## Topics Covered

### Docker Images

* Building custom images
* Image tagging and versioning
* Understanding image layers
* Pulling and managing images

### Docker Containers

* Running containers
* Container lifecycle management
* Multiple containers from a single image
* Interactive container access

### Dockerfile

* FROM
* WORKDIR
* COPY
* RUN
* EXPOSE
* CMD

### Docker Volumes

* Persistent storage
* Volume creation and management
* Data persistence across container recreation
* Volume inspection

### Docker Networking

* Bridge networks
* Custom networks
* Container-to-container communication
* Docker DNS and service discovery

### Docker Compose

* Multi-container application deployment
* Service definitions
* Network configuration
* Volume configuration
* Environment management

### Docker Hub

* Docker image publishing
* Image versioning
* Image tagging
* Pulling and sharing images

### Docker Troubleshooting

* Container failures
* Port mapping issues
* Networking issues
* Volume issues
* Image build failures
* Log analysis
* Container inspection

---

## Labs Completed

### Lab 1 – Build and Run a Node.js Application

* Created a simple Express application
* Verified application functionality before containerization

### Lab 2 – Create Docker Image

* Wrote a Dockerfile
* Built a custom Docker image
* Executed application inside a container

### Lab 3 – Image vs Container

* Created multiple containers from a single image
* Explored container lifecycle
* Used logs, exec, and inspect commands

### Lab 4 – Persistent Storage with Volumes

* Created Docker volumes
* Simulated data loss scenarios
* Verified volume persistence

### Lab 5 – Docker Networking

* Created custom Docker networks
* Connected multiple containers
* Tested container DNS resolution

### Lab 6 – Docker Compose

* Defined multi-container services
* Managed application stack using Compose
* Simplified environment setup

### Lab 7 – Docker Hub

* Tagged images
* Published images to Docker Hub
* Pulled images from registry

### Lab 8 – Troubleshooting Scenarios

* Debugged failed containers
* Investigated networking issues
* Analyzed application logs
* Resolved storage-related problems

---

## Commands Practiced

```bash
docker build
docker run
docker ps
docker stop
docker rm
docker exec
docker logs
docker inspect

docker volume create
docker volume ls
docker volume inspect

docker network create
docker network ls
docker network inspect

docker compose up
docker compose down

docker login
docker tag
docker push
docker pull
```

## Key Learnings

* Difference between Images and Containers
* Container lifecycle management
* Persistent storage using Volumes
* Service communication using Docker Networks
* Multi-container orchestration using Docker Compose
* Image distribution using Docker Hub
* Practical Docker troubleshooting techniques

## Tech Stack

* Docker
* Docker Compose
* Node.js
* Express.js
* Linux
* Git
* GitHub

## Learning Outcome

This repository helped strengthen my understanding of Docker fundamentals, containerized application workflows, storage management, networking concepts, image registries, and troubleshooting practices commonly used in DevOps and Cloud environments.
