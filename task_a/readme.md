## Build the Docker image

```mermaid
graph TD
A[Dockerfile] --> B[PHP Server]
B --> C[task-a Container]
```

```
docker build -t task-a .
```

## Run the container

```
docker run -p 80:80 -d task-a
```

## Stop the container

```
docker stop task-a
```

## Remove the container

```
docker rm task-a
```
