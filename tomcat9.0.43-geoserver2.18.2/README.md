# GEOSERVER 도커 이미지

# link
- [Docker hub](https://hub.docker.com/r/todaksun/postgres13-postgis)

## 이미지 빌드하기
```bash
docker-compose build
```

## 이미지 사용 예시

```bash
docker run -d -p 8080:8080 todaksun/todaksun/tomcat9.0.43-geoserver2.18.2
```

## Geoserver 계정
- 아이디 : admin
- 패스워드 : geoserver

## IMAGE SPECIFICATION
- OS - 20.04.1 LTS (Focal Fossa)
- Java - openjdk version "1.8.0_282"
- Tomcat - 9.0.43
- Geoserver - 2.18.2
- Workdir - /usr/local/tomcat

