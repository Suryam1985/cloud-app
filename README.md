# cloud-app
cloud service

Commands:
#To deploy service in docker container
docker build -t suryamnaidu1985/greet-service:1.0 .

 
# To run the service in docker 
docker run --rm --name greeter -p 8090:8080 suryamnaidu1985/greet-service:1.0

# push to hub.docker.com
docker push suryamnaidu1985/greet-service:1.0