Create directory /etc/redis on host server and copy redis.conf to it.

##### Build the container:

`docker build -t docker-redis .`

##### Run the container:

`docker run -d -v /etc/redis:/etc/redis --name=redis docker-redis`
