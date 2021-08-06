# elastic-apm-docker

docker를 이용한 elastic apm-server, apm-agent, kibana, elasticsearch 연동하기

## Run application & elasticAPM

- run application
```shell
$ cd ./boot-apm-agent

$ docker-compose up --build
```
- run elastic apm
```shell
$ cd ./elastic-apm-env

$ docker-compose up
```