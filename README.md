# Dockerized-Node.js-app-using-Docker_Compose

### Description
- Here the Project counts the visits to our website
- This project contains 4 containers, loadbalancer container that distribute the traffic to 2 web containers built using Node.js and the database of web containers.
- By using docker-compose yaml-file, it will build 3 custom images (nginx, web1, web2) and pull redis image from DockerHub then make 4 containers of those images.
#### Benefit of that project: 
	control the containers status through one command and run those containers as one unit
  Docker compose will create those containers in one Network, so containers can communicate with each other through its name within port, so no need to create network   for them

------------

### How to use the Project

1. ensure that you are in the directory where docker-compose.yml exist
2. Run this command "docker compose up -d"
3. curl http://localhost:80


