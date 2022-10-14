# LaraDocker

## About
This repository contains core code example for environment setup using Laravel and Docker. The repository also uses the following technologies:
* InertiaJS
* Sanctum
* Tailwind
* Vue

## Getting Started

### Install Host Applications
Install [Docker & Docker Compose](https://docs.docker.com/compose/install/) for your particular flavor of OS.

### Building & Running Containers
Once the Docker engine is running on the host machine, open a terminal in the projects root directory and enter the following commands:
* `docker-compose build` - This builds the required Docker containers. Will take a while initially,
but subsequent builds won't take long.
* `docker-compose up` - This starts all the development Docker containers.
* `docker-compose exec app composer install` - This downloads all the application dependencies via Composer.
- `docker-compose exec app php artisan migrate` - This will populate the database with the initial data.