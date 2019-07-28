# docker-ping
A docker container image for network administrators

This docker image is created using the concept of docker file.

Basically, it is a network administering container image which can be used to check the connection between host and a client using ping command. This image is committed using alpine container image. By default while running this image it will ping to www.google.com. You can simply pass any parameter while running this image to check the connection between your system and the given address. (Example: 1. docker run kjv3615/ping:latest 2. docker run kjv3615/ping:latest someaddress.com 3. docker run kjv3615/ping:latest X.X.X.X)

You can get this image from (https://cloud.docker.com/repository/docker/kjv3615/ping) or using the docker command (docker pull kjv3615/ping)
