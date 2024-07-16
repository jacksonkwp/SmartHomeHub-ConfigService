FROM eclipse-temurin:21-jdk-alpine
LABEL authors="Pawan_Bhandari1@baylor.edu"

RUN apk --no-cache add bash curl

WORKDIR /workspace/app
COPY target/*.jar config-server.jar

ENTRYPOINT ["java", "-jar", "config-server.jar"]