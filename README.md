

```bash

docker build -t cont-int .

#docker run -it --net=host --add-host=moby:127.0.0.1 -p 8080:8080 ci
docker run -it --net=host -p 8080:8080 cont-int
```


secureshell docker container

```
docker exec -i -t b6415206b534 /bin/bash

cat /var/jenkins_home/secrets/initialAdminPassword 
f87c863f34a14cd5a6589514412981ff
```
