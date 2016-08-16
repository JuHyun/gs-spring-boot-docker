# How to know correct url information when using docker-machine at Mac OSX

If you use docker-machine, you will encounter error when you access http://localhost:8080.

```
$ docker-machine ls
NAME      ACTIVE   DRIVER       STATE     URL                         SWARM   DOCKER    ERRORS
default   -        virtualbox   Running   tcp://192.168.99.100:2376           v1.12.0
dev       -        virtualbox   Stopped                                       Unknown
```

you have to access url ip

http://192.168.99.100:8080
