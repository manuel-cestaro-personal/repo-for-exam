# repo-for-exam
I used this repo for the first part of the final exam of the ITS course DevOps & CyberSecurity 2020-2022.

## Objective
The objective of the first part of the task was to containerize a supplied application. 
The application must be functional in any environment through docker compose following the best practices.
Specifically, it requires:
- modify the application code to be compatible with use in a container and launch in different environments;
- define Dockerfile application;
- define yaml docker compose file for the entire stack;
- use of environment variables;
- the use of volumes (named volume) for data persistence (not bind mounts);

## Start application
- clone the repo
- `cd ./repo-for-exam/backend`
- `docker buid -t backend-img:v1.0 .`
- `cd ..`
- change env variables if you want
- `docker-compose up -d`  &#128521;
- use `docker ps -a` to check the containers

## Conclusions