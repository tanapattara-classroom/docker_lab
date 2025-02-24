## Build the Docker image

```mermaid
graph TD
A[Dockerfile] --> B[Node.js Server]
B --> C[task-b Container]
```

```
docker build -t task-b .
```

## Run the container

```
docker run -p 3000:3000 -d task-b
```

## Stop the container

```
docker stop task-b
```

## Remove the container

```
docker rm task-b
```
