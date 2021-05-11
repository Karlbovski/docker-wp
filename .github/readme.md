# Docker Wordpress Starter

Simple development environment for Wordpress.

## Stack docker images
- [Wordpress:latest](https://github.com/docker-library/wordpress/blob/394c79eafd5b345514f87cec590577e641c030ef/latest/php7.4/apache/Dockerfile)
  - php7.4
  - Apache
- [MySql 5.7](https://github.com/docker-library/mysql/blob/b11f06b0d202e7b0f97b000e158fc4fc869d2194/5.7/Dockerfile.debian)

## Usage
- Create dedicated volumes for dev/production and use them in the `docker-compose` file.

- run `docker-compose up -d`

## Resources
[Docker Docs](https://docs.docker.com/)

[Volumes in Docker](https://docs.docker.com/storage/volumes/)

[Volumes with Docker-Compose](https://docs.docker.com/compose/compose-file/compose-file-v3/#volume-configuration-reference)