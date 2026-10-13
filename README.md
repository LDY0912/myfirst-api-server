# myfirst-api-server

SKALA DevOps 실습용 Spring Boot 앱. Java 21, Maven 사용.

```sh
mvn clean package -DskipTests
docker build --platform linux/amd64 -t myfirst-api-server:1.0 .
```

Kustomize: `kustomize/overlays/dev`, namespace `class-6`.
