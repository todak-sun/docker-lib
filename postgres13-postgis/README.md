# POSTGRES + POSTGIS 도커 이미지

# link
- [Docker hub](https://hub.docker.com/r/todaksun/postgres13-postgis)

## 이미지 빌드하기
```bash
docker-compose build
```

## 이미지 사용 예시

```bash
docker run -d -p 5432:5432 todaksun/postgres13-postgis
```

## IMAGE SPECIFICATION

- PostgreSQL - 13.2-1.pgdg100+1
- PostGIS - 3.1.1+dfsg-1.pgdg100+1


## 주의사항

테스트용으로 생성한 이미지입니다.
따라서 실 사용시, 추가 작업이 필요할 수 있습니다.

개발환경에서 사용하더라도, 꼭 볼륨 매핑 후 사용하시길 권합니다.

