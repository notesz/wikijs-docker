# wikijs-docker

Docker for Wiki.js. \
The Wiki.js is an Open Source Wiki software.

Repository: https://github.com/notesz/wikijs-docker \
Wiki.js website: https://js.wiki/

## Goal of this project

The goal of this container is to provide an example for running Wiki.js.

## Usage

### Preparation

1. Download the files
2. Create a .env from .env.example and modify it in the main folder (the example contains my recommended settings)

### Run container

In the main directory run the container with docker-compose

```shell
docker-compose up -d
```

When your environment was launched you can open it in your browser: \
http://localhost

### Stop container

In the main directory stop tha container with docker-compose

```shell
docker-compose down
```
