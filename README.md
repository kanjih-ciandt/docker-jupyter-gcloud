# docker-jupyter-gcloud

#### Build Dockfile
```sh
$ docker build -t <image_name> .
```

#### Run docker

```sh
$ docker run -p 8888:8888 <image_name>
```


#### Access docker image running

```sh
$ docker exec -ti $(docker ps | grep "<image_name>" | awk '{ print $1 }')  /bin/bash
```

#### Gcloud init

```sh
jovyan@XXXXX:~$ gcloud init
```


