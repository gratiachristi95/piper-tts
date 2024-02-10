# piper-tts

# Intro

This repository contains a Dockerfile of [Debian](https://www.debian.org/) for [Docker](https://www.docker.com/)'s [automated build](https://hub.docker.com/r/gigolo0937/debian) published to the public [Docker Hub Registry](https://registry.hub.docker.com/).

[debian:testing](https://hub.docker.com/_/debian)

# Installation

1. Install [Docker](https://www.docker.com/).

2. Install [Docker-Compose](https://docs.docker.com/compose/install/linux/).

3. [Clone](https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository) the repository 
  
4. Run docker-compose up -d

5. Find the name of the docker container using docker ps

6. Run a bash script to use piper-tts using docker exec -it --user root name-of-container bash
   Replace the name-of-container with the name found in step 5
