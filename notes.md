### Pull image
```zsh
docker pull nginx
```
### Show running containers
```zsh
docker ps
```
### Show all containers
```zsh
docker ps -a
```
### Attach image to a container with port mapping from host to container (-d means run in the background)
```zsh
docker run -d -p 8080:80 nginx:latest
```
### Stop container
```zsh
docker stop container_name/container_id
```
### Remove container (-f means force remove)
```zsh
docker rm -f container_name/container_id
```