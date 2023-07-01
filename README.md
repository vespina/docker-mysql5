# docker-mysql5
MySQL5 docker container

This composer script will create two containers:

Name | Contents
-----|---------
mysql5-db | MySQL 5.7 server
mysql5-adminer | MySql Web Admin


##### IMPORTANT!
Before building the containers, edit *stack.yml* to configure the setup as you neeed.


##### TO BUILD:
    docker-compose build
     
##### TO RUN:
    docker-compose up -d
     
##### TO STOP:
    docker-compose stop
