# Docker
Compatibility on different libraries on different OS
eg:- Nodeexpress(web), MongoDB, Messaging, Orchestration [build it across all OS which works the same way]



Docker - run each component in a separate container without modifying the main OS. [separate container]

Container [same OS kernel, processes, networks, Mounts]


same OS kernel - Linux kernel which makes the container runs on all linux based distributions [redhat, debian]

Docker - package and containerize applications which can be transferred and applied anywhere.

dockerhub [public docker repo]


Container vs image
------------------
image - an ami 
container - running process built using image.

dockerfile > build image > deploy the application


https://docs.docker.com/engine/install/ubuntu/
Install docker using the convenience script


 sudo docker run docker/whalesay cowsay hello


 run docker with environment options 

 docker run -d --name=mysql-db -e MYSQL_ROOT_PASSWORD=password mysql
 
