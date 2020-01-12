# Docker Command Line Interface

[home](../README.md)

1. [`docker run`](#docker-run)
1. [`docker start`](#docker-start)
1. [`docker stop`](#docker-stop)
1. [`docker rm`](#docker-rm)
1. [`docker rmi`](#docker-rmi)
1. [`docker pull`](#docker-pull)
1. [`docker images`](#docker-images)

## `docker run`
If image exists start it, if not download it from registry -> then start.
`-d` run in background.
`-it` interact
## `docker start`
docker start for `start`ing a stopped containers

## `docker stop`
docker stop

## `docker rm`

`>docker rm $(docker ps -aq)`
removes all docker containers

## `docker rmi`
similar to above 'rm' but for images not containers
`>docker rmi $(docker images -q)`

## `docker pull`
copies image from registry local

## `docker images`
lists all the images 