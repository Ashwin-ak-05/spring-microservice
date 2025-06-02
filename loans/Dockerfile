FROM openjdk:17-jdk-slim

MAINTAINER ashwin.com

COPY target/loans-0.0.1-SNAPSHOT.jar loans-0.0.1-SNAPSHOT.jar

ENTRYPOINT ["java","-jar","loans-0.0.1-SNAPSHOT.jar"]

#docker run -p 8080:8080 ashwinkumar05/accounts:s
#mvn compile com.google.cloud.tools:jib-maven-plugin:dockerBuild -Dimage=ashwinkumar05/loans:s4
