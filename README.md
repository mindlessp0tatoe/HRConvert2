# HRConvert2

Fork of HRConvert2-Docker which is forked from https://github.com/zelon88/HRConvert2 
A self-hosted, drag-and-drop, & nosql file conversion server that supports 62x file formats.

## Docker Hub
https://hub.docker.com/r/syberslxt/hrconvert2
`docker pull syberslxt/hrconvert2:latest`


## Dockerfile (Building the image yourself)

1. `git clone https://github.com/syberslxt/HRConvert2`
2. `Edit config.php`
3. `docker build -t hrconvert2 .`
4. `docker images,copy the image ID`
5. `docker run -i -t hrconvert2`
 

## Docker Compose Setup

1. `git clone https://github.com/syberslxt/HRConvert2`
2. Edit config.php - make sure to atleast set the salts and the URL
3. `docker-compose up -d`


### Updates 2023-10-26
* updated base image to ubuntu 23.10
* updated HRConvert2 from 2.9.2 to 3.1

### Updates 10/05/2022
* updated base image to ubuntu 20.04
* updated php from 7.2 to 7.4
* updated HRConvert2 from 2.6 to 2.9.2

