FROM tomcat:9.0.43-jdk8-adoptopenjdk-openj9

RUN apt update && apt -y install wget unzip
RUN mkdir tmp && wget -q https://sourceforge.net/projects/geoserver/files/GeoServer/2.18.2/geoserver-2.18.2-war.zip -O ./tmp/geoserver.zip
RUN unzip -q ./tmp/geoserver.zip -d ./tmp
RUN mv ./tmp/geoserver.war ./webapps/geoserver.war

RUN rm -rf ./tmp

