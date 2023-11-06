# Docker
To run the docker run 
```
docker build -t complex:Dockerfile --progress=plain --no-cache . &> build.log
```

now to run it you use 
```
docker run --name complex --rm -e POSTGRES_PASSWORD=gian -e POSTGRES_USER=gian -p 5434:5432 complex:Dockerfile
```
