## Learning-docker

## shows all images
`docker images`

## docker image name syntax
`saalimmushtaq/gcc-4.9:1`
> saalimmushtaq is the name of the repository,gcc-4.9 is the name of the image,1 is the image tag  


## to start
`service docker start`

## to see running containers
`docker ps`

## to find out images in docker hub
`docker serach imagename`

## to see running and stopped containers
`docker ps -a`

## to download image from dockerhub to local machine
`docker pull imagename`

## to give name to the container
`docker run -it --name contname imagename /bin/bash`

## to check service is start or not`
`service docker start`

## to start container
`docker start containername`

## to go inside the container
` docker attach containername` 

## to stop the container
`docker stop containername`

## to delete the container
`docker rm containername`

## to create image out of a dockerfile
`docker build -t myimage .`

## to create a container from any image
`docker run -it --name containername imagename /bin/bash`

## to create image from the container
`docker commit containername imagename`


## to see which OS you are using on the container
`cat /etc/os-release`

## to share volume with another container
`docker run -it --name containername2 --privileged=true --volumes from containername1`

## Remove all unused local volumes
~docker volume prune~


## Commands used inside a Dockerfile


## FROM
`this image must be on top of the dockerfile`

## RUN
`to execute commands,it will create a layer in image`

## WORKDIR 
`to set working directory for a container`

## COPY 
`copy files from a local sytem,we need to provide source and destination.

## ADD
`similar to copy but it provides a feature to download files from internet`

## EXPOSE
`to expose ports`

## CMD 
`execute commands`

## ENV
`environment variable`






