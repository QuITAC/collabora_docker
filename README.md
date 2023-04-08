Collabora docker web service for integration into Nextcloud as Nextcloud Office | digital infrastructure of Queerreferat Aachen

## Prerequisites

- Have the proxy_docker service started

## Deploy

1. run `docker-compose build --pull` to pull the most recent base images and build the custom dockerfiles
2. start collabora with `docker-compose up -d`
3. install `Nextcloud Office` as an app for Nextcloud
4. go into the Settings and enter the domain for the collabora service

## Update

repeat steps 1 and 2 of the deployment
