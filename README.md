# Usefull links
https://www.codeproject.com/Tips/5336563/Run-Database-and-GUI-Clients-in-Docker

# Docker commands
docker-compose build
docker-compose up
docker-compose down
docker-compose logs -f [service name]
remove the docker image:

docker image ls
docker rmi imagename
remove the volume:

docker volume ls
docker volume rm yourvolume
remove the container:

docker ps -a
docker rm yourcontainer
Then:

docker-compose up

remove
/var/lib/mysql/
# .ENV
MYSQL_DATABASE=
MYSQL_USER=
MYSQL_PASSWORD=
MYSQL_ROOT_PASSWORD=