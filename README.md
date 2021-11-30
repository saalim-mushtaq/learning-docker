## Learning-docker

## to check docker version
`docker -v`

## shows all images
`sudo docker images`

## docker image name syntax
`saalimmushtaq/gcc-4.9:1`
> saalimmushtaq is the name of the repository,gcc-4.9 is the name of the image,1 is the image tag  


## to start
`sudo service docker start`

## to see running containers
`sudo docker ps`

## to find out images in docker hub
`sudo docker serach imagename`

## to see running and stopped containers
`sudo docker ps -a`

## to download image from dockerhub to local machine
`sudo docker pull imagename`

## to give name to the container
`sudo docker run -it --name contname imagename /bin/bash`

## to check service is start or not`
`sudo service docker start`

## to start container
`sudo docker start containername`

## to go inside the container
`sudo docker attach containername` 

## to stop the container
`sudo docker stop containername`

## to delete the container
`docker rm containername`

## to create image out of a dockerfile
`sudo docker build -t myimage .`

## to create a container from any image
`sudo docker run -it --name containername imagename /bin/bash`

## to create image from the container
`sudo docker commit containername imagename`


## to see which OS you are using on the container
`sudo cat /etc/os-release`

## to share volume with another container
`sudo docker run -it --name containername2 --privileged=true --volumes from containername1`

## Remove all unused local volumes
`~sudo docker volume prune~`

## to push dockerimage to dockerhub
`sudo docker push dockerid/imagename`

## to pull dockerimage from dockerhub
`sudo docker pull dockerid/imagename`

## to stop all running containers
`sudo docker stop $(docker ps -a -q)`

## to delete all stopped containers 
`sudo docker rm $(docker ps -a -q)`

## to delete all images
`sudo docker rm -f $(docker images -q`


## Commands used inside a Dockerfile


## FROM
`this image must be on top of the dockerfile`

## RUN
`to execute commands,it will create a layer in image`

## WORKDIR 
`to set working directory for a container`

## COPY 
`copy files from a local sytem,we need to provide source and destination`

## ADD
`similar to copy but it provides a feature to download files from internet`

## EXPOSE
`to expose ports`

## CMD 
`execute command`


## ENV
`environment variable`






