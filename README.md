# docker-jupyter-gcloud

#### Build Dockfile (if you are creating your own docker)
```sh
$ docker build -t <image_name> .
```

#### Run docker from docker hub

```sh
$ docker pull hkanjih/docker-jupyter-gcloud
$ docker run -p 8888:8888 hkanjih/docker-jupyter-gcloud
```


#### Access docker image running from docker hub

```sh
$ docker exec -ti $(docker ps | grep "hkanjih/docker-jupyter-gcloud" | awk '{ print $1 }')  /bin/bash
```

#### Gcloud init

```sh
jovyan@XXXXX:~$ gcloud init
```


