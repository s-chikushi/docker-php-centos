# Start project
1. Copy your project under path "./server/" .
2. Fix "./docker/apache/conf/httpd.conf".
3. Now you can start. Execute the following command.
```
$ docker-compose up -d --build
```
> Note: you may wait about 5 minites.
4. check localhost:3000 .
> Note: if you want to use adminer, you will access localhost:8080.
5. If you want to finish your project, execute the following command.
```
$ docker-compose down
```

# Support commands
```
$ docker ps
```
check docker status

```
$ docker exec -it {NAMES} bash
```
Run a command in a running container.
You can control as like CentOS server in the container.
