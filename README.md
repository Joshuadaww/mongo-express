How to use this image
<br>&emsp;$ docker run --network some-network -e ME_CONFIG_MONGODB_SERVER=some-mongo -p 8081:8081 mongo-express
<br>&emsp;Baca artikel "https://hub.docker.com/_/mongo-express"
<br>
<br>
<br>
Downloading an Image
<br>&emsp;$ docker search mongo-express
<br>
<br>
<br>
Command :
<br>&emsp;build and run container : $ docker-compose up -d
<br>&emsp;check list container : $ docker ps --format "table{{.ID}}\t{{.Names}}\t{{.Status}}\t{{.Ports}}"
<br>
<br>
<br>
Docker's container log
<br>&emsp;$ docker logs mongo-express
<br>


