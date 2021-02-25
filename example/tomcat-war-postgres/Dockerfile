FROM tomcat:9.0.43-jdk8-adoptopenjdk-openj9

EXPOSE "8080"

ENV DB_URL jdbc:postgresql://postgres:5432/postgres
ENV DB_USERNAME postgres
ENV DB_PASSWORD postgres

COPY ./war/app.war ./webapps/ROOT.war

WORKDIR /usr/local/tomcat

