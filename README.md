mvn clean package 

docker build -t docker-multi-stage-build-demodocker:1.0-SNAPSHOT . 

docker run -d -p 8080:8080  docker-multi-stage-build-demodocker:1.0-SNAPSHOT 

docker ps 

docker images 
