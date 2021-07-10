# docker-sonarqube

```shell
docker network create sonarqube
```

```shell
docker pull sonarqube:lts
docker run -d --name sonarqube \
--net sonarqube \
-p 9000:9000 \
sonarqube:lts
```