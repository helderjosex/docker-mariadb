# Mariadb Docker
This is an unofficial, open-source for Maiadb based projects that run on Docker-Compose. 

    Mariadb latest
    GUI for mariadb
    
## Usage
You are up and running in three simple steps:

$ cd mariadb-docker

$ docker-compose up --build -d 
 
You can just open your browser at:

http://localhost:8080 or you can get the container IP: docker inspect CONTAINER ID | grep IPAddress

To use the CLI to access mariadb directly execute the following:

$ docker exec -it mariadb mysql --user=root --password=password