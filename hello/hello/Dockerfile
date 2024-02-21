FROM openjdk:17
ARG JAR_FILE=/hello/hello/build/libs/hello-0.0.1-SNAPSHOT.jar
COPY ./app.jar app.jar
ENTRYPOINT ["java","-jar","/app.jar"]