## Learning-docker

## docker images
`shows all images

## docker image name syntax
`a/b:1`
`a represents the name of the repository,b represents the name of the image,1 represents the specific version of the image` 

## docker build
`creates image from dockerfile`

## service docker start
`to start`

## docker ps
`to see running containers`

## docker search imagename
`to find out images in docker hub`

## docker ps-a
`to see running and stopped containers`

## docker pull imagename
`to download image from dockerhub to local machine`

## docker run -it --name contname imagename /bin/bash
`to give name to the container`

## service docker start
`to check service is start or not`

## docker start containername
`to start container`

## docker attach containername
`to go inside container`

## docker stop containername
`to stop container`

## docker rm containername
`to delete container`

## docker build -t imagename .
`to create image out of a dockerfile`

## docker run -it --name containername imagename /bin/bash
`to create container from any image`

## docker commit containername imagename
`to create image from container`


## cat /etc/os-release
`to see which OS you are using on the container`

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

## docker run -it --name containername2 --privileged=true --volumes from containername1
`to share volume with another container`

## docker volume prune
~Remove all unused local volumes~

##



