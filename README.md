# Dockerized React Nest

```
 ██████╗   ██████╗   ██████╗ ██╗  ██╗ ███████╗ ██████╗  ██╗ ███████╗ ███████╗ ██████╗
 ██╔══██╗ ██╔═══██╗ ██╔════╝ ██║ ██╔╝ ██╔════╝ ██╔══██╗ ██║ ╚══███╔╝ ██╔════╝ ██╔══██╗
 ██║  ██║ ██║   ██║ ██║      █████╔╝  █████╗   ██████╔╝ ██║   ███╔╝  █████╗   ██║  ██║
 ██║  ██║ ██║   ██║ ██║      ██╔═██╗  ██╔══╝   ██╔══██╗ ██║  ███╔╝   ██╔══╝   ██║  ██║
 ██████╔╝ ╚██████╔╝ ╚██████╗ ██║  ██╗ ███████╗ ██║  ██║ ██║ ███████╗ ███████╗ ██████╔╝
 ╚═════╝   ╚═════╝   ╚═════╝ ╚═╝  ╚═╝ ╚══════╝ ╚═╝  ╚═╝ ╚═╝ ╚══════╝ ╚══════╝ ╚═════╝


 ██████╗  ███████╗  █████╗   ██████╗ ████████╗        ███╗   ██╗ ███████╗ ███████╗ ████████╗
 ██╔══██╗ ██╔════╝ ██╔══██╗ ██╔════╝ ╚══██╔══╝        ████╗  ██║ ██╔════╝ ██╔════╝ ╚══██╔══╝
 ██████╔╝ █████╗   ███████║ ██║         ██║    █████╗ ██╔██╗ ██║ █████╗   ███████╗    ██║
 ██╔══██╗ ██╔══╝   ██╔══██║ ██║         ██║    ╚════╝ ██║╚██╗██║ ██╔══╝   ╚════██║    ██║
 ██║  ██║ ███████╗ ██║  ██║ ╚██████╗    ██║           ██║ ╚████║ ███████╗ ███████║    ██║
 ╚═╝  ╚═╝ ╚══════╝ ╚═╝  ╚═╝  ╚═════╝    ╚═╝           ╚═╝  ╚═══╝ ╚══════╝ ╚══════╝    ╚═╝
```

In this repository, you will find the code example of a dockerized Nest and React applications in a monorepo.

## Prerequisites

1.  Install Make `sudo apt install make`.
2.  Install [Docker](https://docs.docker.com/engine/install/ubuntu/) and [Docker Compose](https://docs.docker.com/compose/install/).

## Configure

You can get this porject up and running on your local dev environment in 1 minute.
You just need to create and fill the environment variables file `.env` from the `.env.example` file.

## Run

In order to run this project in your local machine, run the `make local` command on the project root folder.
This will run `docker-compose down && docker-compose up -d --build --remove-orphans` and create the Docker containers.
