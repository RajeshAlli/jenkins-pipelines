FROM tomcat:latest
MAINTAINER rajesh
COPY var/lib/jenkin/*.war user/local/tomcat
EXPOSE 8080
USER monjin
ENTRYPOINT ['sh','catalina.sh']

-------------
in docker i do build dockerfile and image
tag docker file
docker login
docker push to docker privetae registry
images   - its a group of commands to create os env 
containers
volumes
networks
registries

-------------
docker build -t dockerfile
docker run -d imagename
docker exec -it containername /bin/sh
docker run -d redis -p 5000:5342 
docker run -d redis -p 5000:3452 --image=sdjsd
docker tag username/repo name:imagename
docker login
docker push username/repo name:imagename
docker rmi imagename

docker file
FROM
MINTAINER
RUN
CMD
ENTRYPOINT