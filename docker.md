# Docker


Basics
docker-compose builds from a yaml file
docker run is entirely command line based
Also docker run can only start one container

Build and run a docker container named “myPostgresDb” from an image named “postgres” with port forwarded to localhost.

docker run
    --name myPostgresDb
    -p 5455:5432
    -e POSTGRES_USER=postgresUser
    -e POSTGRES_PASSWORD=postgresPW
    -e POSTGRES_DB=postgresDB
    -d
    postgres



docker run postgres -e POSTGRES_PASSWORD="123" -e POSTGRES_HOST_AUTH_METHOD="trust" -dp 5432:5433





https://stackoverflow.com/questions/58522952/linking-my-django-docker-container-to-a-postgres-container
- [ ] Docker
    - [ ] run make migrations and migrate before running or dickering.
    - [ ] Dockerizing 
    - [ ] https://hub.docker.com/r/tzenderman/docker-pyenv
    - [ ] build
        - [ ] mkdir -p .pip_cache
        - [ ] docker build -t markdown:1.0 .
- [ ] docker run -it -p 8020:8020 \
     -e DJANGO_SUPERUSER_USERNAME=admin \
     -e DJANGO_SUPERUSER_PASSWORD=sekret1 \
     -e DJANGO_SUPERUSER_EMAIL=admin@example.com \
     markdown:1.0
    - [ ] docker ps -l
    - [ ] docker start/stop <container id>  # This does not persist a reboot
    - [ ] docker run -d --restart unless-stopped redis  # Does this persist
    - [ ] docker rm <container id> -f # to remove a container
    - [ ] http://174.138.125.25:8020
    - [ ] Read this next : don’t need to rebuild container each time.
