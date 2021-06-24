Created a normal api using flask,uswgi and nginx using docker and pushed the image in the docker hub in the following link --

https://hub.docker.com/repository/docker/divincode/practice-api

to run the image use the following command -
sudo docker run -p 8080:8080 -u 112233 practice-api:latest

and api is exposed in the follwoing links - http://192.168.0.108:8080/ and /echo_request
