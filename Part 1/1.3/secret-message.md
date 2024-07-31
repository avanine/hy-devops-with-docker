```
docker run devopsdockeruh/simple-web-service:ubuntu
```
```
docker ps -a

CONTAINER ID   IMAGE                                      COMMAND                  CREATED              STATUS                          PORTS     NAMES
00d5747fd009   devopsdockeruh/simple-web-service:ubuntu   "/usr/src/app/server"    32 seconds ago       Up 31 seconds                             quizzical_lehmann
```
```
docker exec -it 00d bash
```
```
tail -f ./text.log
```
Secret message is: 'You can find the source code here: https://github.com/docker-hy'
