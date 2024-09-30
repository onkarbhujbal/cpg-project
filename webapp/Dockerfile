FROM tomcat:jdk11-openjdk-slim-buster

MAINTAINER onkarbhujbal@gmail.com

COPY /target/demo.war /usr/local/tomcat/webapps/docker-war-demo.war

CMD ["catalina.sh", "run"]