# FAI-LiveKit-Server

## Build the Docker image

```bash
docker build -t livekit-server:1.0 -f Dockerfile.cli .
```

## Run the Docker container

```bash
docker run -d \
    --name livekit-server \
    --network host \
    livekit-server:1.0
```