# Docker: getting started

Dockerfile builden naar een image:
```
docker build -t docker-lecture .
```

Docker image runnen als container:
```
docker run -d -p 80:80/tcp --name docker-lecture0 docker-lecture
```

Draaiende Docker containers inzien:
```
docker ps
```

Alle Docker containers inzien:
```
docker ps -a
```

Draaiende Docker container stoppen:
```
docker stop [naam container]
```

Bestaande Docker container starten:
```
docker start [naam container]
```