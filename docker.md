# Docker
## docker cli
```shell
# search docker version
docker
# search docker images
docker search {name}
# pull docker iamges
docker pull {name}
# run docker
# -d: run backend
docker run --name {rename} -d {name}:{version}
# view running docker container
docker ps
# -a all
docker ps -a
# stop docker {id}
docker stop {id}
# start docker
docker start {id}
# remove docker container
docker rm {id}
# docker run
# -d run backend
# -p map the host port to the container port
docker run -d -p {host port}:{container port} {name}
# view log
docker logs {name}/{id}
# view iamges
docker images
# remove docker image
docker rmi {image id}
# enter running docker container
docker exec -it {container name}/{container id}
# exit running docker container
exit
```

## debug docker with Intellij IDEA
