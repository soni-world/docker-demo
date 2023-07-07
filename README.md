# docker-demo
simple docker demo

created teh spring boot simple web application
Needed to setup docker
create the mvn clean build
take the jar path and create the docker file
can create custom file name of jar by modifying the pom.xml build section

 create the docker image -> docker build -t docker-demo.jar .

docker image created , can check with teh command -> docker image ls

now we can run the spring boot application from docker -> docker run -p 9090:8080 docker-demo.jar

Here 8080 is the local port exposed in docker and then the 9090 is the external port to access the service.

Also, the docker-demo.jar is the docker image name.

Now the docker image is running inside the docker container.
