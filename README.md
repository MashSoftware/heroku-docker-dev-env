# Heroku Docker based development environment

Uses the official Heroku and add-on providers images and versions in line with Heroku's production environment.

## Prerequisites
* [Docker Compose](https://docs.docker.com/compose/)
* [Docker Engine](https://docs.docker.com/engine/) (on Windows & macOS)

## Getting Started

```bash
git clone git@github.com:MashSoftware/heroku-docker-dev-env.git
cd heroku-docker-dev-env/apps
git clone git@github.com:MashSoftware/thing-api.git && git@github.com:MashSoftware/thing-ui.git
docker-compose up
```
