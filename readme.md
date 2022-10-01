# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant
dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md)
and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main`
from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

### Clone the repo and set it up locally

### Install Docker

https://docs.docker.com/engine/install/

Also recommended to install docker GUI: https://www.docker.com/products/docker-desktop/

### Check If Docker is installed correctly

```
$ docker -v
Docker version 20.10.17, build 100c701

$ docker-compose -v
Docker Compose version v2.6.1

```

### Docker compose up at the root file

```
$ docker-compose up

```

### Verify if frontend and backend is running locally

backend: http://localhost:3000/api/ping

frontend: http://localhost:3001/register
