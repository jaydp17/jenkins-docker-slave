# Jenkins Docker Slave

[![Docker Build Status](https://img.shields.io/docker/build/jaydp17/jenkins-slave.svg)](https://hub.docker.com/r/jaydp17/jenkins-slave/)

An image similar to [evarga/jenkins-slave](https://hub.docker.com/r/evarga/jenkins-slave/), i.e. it can be used as the base image for a Jenkins slave.
It takes the [evarga/jenkins-slave](https://hub.docker.com/r/evarga/jenkins-slave/) image and adds a few essential tools (like `curl` & `git`) that make it easier to build stuff inside the container.

# Usage
You create your own slave image based on this
```Dockerfile
# Dockerfile
FROM jaydp17/jenkins-slave

# Install/ Copy whatever you want
```
