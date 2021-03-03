# 도커 라이브러리

개발을 진행하며 프로젝트 환경 세팅을 구성하는데 너무 애를 먹는다.
그러던 중 도커라는 기술을 알게 되었고 이를 학습해보았다.

개발시 필요했던 이미지들을 명세해 보관한 레포지토리다.

대부분의 이미지는 docker-compose를 사용해 빌드하며, 
이미지 명세는 Dockerfile를 사용한다.

## Dockerhub 에 올려둔 이미지 목록

| 이미지명                     | 설명                      | 링크                                             |
| ---------------------------- | ------------------------- | ------------------------------------------------ |
| postgres13-postgis           | Postgres + PostGIS        | [link](./postgres13-postgis/README.md)           |
| tomcat9.0.43-geoserver2.18.2 | Geoserver2.18 on Tomcat 9 | [link](./tomcat9.0.43-geoserver2.18.2/README.md) |


## Docker 사용 정리 예시
| 제목                                                                     | 링크                                            |
| ------------------------------------------------------------------------ | ----------------------------------------------- |
| jar로 build한 application을 openjdk 컨테이너를 활용해 실행하기           | [link](./example/openjdk-8-jar/README.md)       |
| war로 build한 application을 tomcat과 postgres 컨테이너를 활용해 실행하기 | [link](./example/tomcat-war-postgres/README.md) |
