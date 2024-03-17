---
title: Docker
sidebar_position: 2
---

**Image Management:**

- `docker pull <image>`: Download an image from a registry (e.g., Docker Hub)
- `docker images`: List all local images
- `docker rmi <image>`: Remove an image

**Container Management:**

- `docker run -it <image>`: Run an interactive container from an image
- `docker ps`: List all running containers
- `docker stop <container>`: Stop a running container
- `docker rm <container>`: Remove a stopped container

**Building Images:**

- `docker build -t <image_name> .`: Build an image from a Dockerfile in the current directory

**Network:**

- `docker network create <network_name>`: Create a new network
- `docker run -d --network <network_name> <image>`: Run a container attached to a specific network

**Volumes:**

- `docker run -v <host_path>:<container_path> <image>`: Mount a local directory to a container path

**Remember:** Replace `<image>`, `<container>`, `<image_name>`, etc. with your desired names.

**Bonus:**

- `docker search <term>`: Search for images on Docker Hub
- `docker login`: Login to Docker Hub (for private images)
- `docker help <command>`: Get detailed help for a specific command
