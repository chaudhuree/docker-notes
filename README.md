# docker-notes
Command List:
docker run nginx
docker run -p 8080:80 nginx 
docker ps 
docker ps -a 

ufw allow 8080 
docker stop <first few letters of Container ID>
docker run -d nginx // starts nginx docker container in background
docker rm CID
docker rm -f CID/name // delete a running container forcefully
docker start CID/name
 
touch this.png
docker cp this.png <first few letters of Container ID>:th.txt
docker exec -it <first few letters of Container ID> bash

docker cp <first few letters of Container ID>:mine.txt this.uu // copy from container to source
docker exec -it <Container_ID> bash // executes a command inside an existing container
docker commit container 

docker images 
docker image ls 
docker system prune
