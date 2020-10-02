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
`-d` detached / run in background.
`-it` interactive

## `docker start`
docker start for `start`ing a stopped containers

## `docker stop`
docker stop for stopping containers


## `docker pull`
copies image from registry to local

## `docker images`
lists all the images 


## `docker rmi`
removes image
`>docker rmi $(docker images -q)` removes all

## `docker rm`
`>docker rm $(docker ps -aq)`
removes all docker containers.  Similar to above but for containers

