# Docker Ubuntu Image Creation

## 1. Pull the Ubuntu Image
```bash
docker pull ubuntu:latest

docker run -it --name ubuntu-container ubuntu:latest bash

docker run -dit --name ubuntu-container ubuntu:latest bash

docker exec -it ubuntu-container bash

docker run -dit \
  --name ubuntu-container \
  --mount type=bind,source=/Volumes/MySSD/ubuntu-data,target=/data \
  ubuntu:latest bash

```

## 2. Install Software inside Ubuntu

```bash
apt-get update && apt-get install -y openssh-server nginx

```
