# dockers

docker pull nginx: pull images

docker run nginx: create containers

docker run -d nginx: create detached containers, which means still be able to run the terminal

docker ps: check current running containers

docker images: check current containers

docker stop ee5eba853e03: close the container ID

docker run -d -p 9000:80 nginx: create a docker and load to the local. can be opened on website

docker logs 7facd044b3ad: check the container is runing

docker ps -a: show all conteners, even some of them already stopped.
