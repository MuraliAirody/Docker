# Docker Basic Commands

## Container Management
| Command | Description |
|---------|-------------|
| `docker ps` | List running containers. |
| `docker ps -a` | List all containers (running + stopped). |
| `docker start <name>` | Start a stopped container. |
| `docker stop <name>` | Stop a running container. |
| `docker rm <name>` | Remove a container. |

## Image Management
| Command | Description |
|---------|-------------|
| `docker images` | List all downloaded images. |
| `docker pull <image>` | Download an image from Docker Hub. |
| `docker rmi <image>` | Remove an image. |
| `docker save <image> -o file.tar` | Save image to tar file. |
| `docker load -i file.tar` | Load image from tar file. |

## Running Containers
| Command | Description |
|---------|-------------|
| `docker run -it --name <name> <image> bash` | Run container interactively. Stops on exit. |
| `docker run -dit --name <name> <image> bash` | Run container in detached mode (keeps running after exit). |
| `docker exec -it <name> bash` | Attach to a running container’s shell. |

## System Info
| Command | Description |
|---------|-------------|
| `docker info` | Show Docker system information. |
| `docker context use default` | Switch to default Docker context. |

## Exiting a Container
- `exit` → Leave container shell.
- `Ctrl+D` → Shortcut to exit.


