FROM adoptopenjdk/openjdk11:jre-11.0.8_10-debianslim

ARG JAR_FILE=build/libs/*.jar

COPY ${JAR_FILE} app.jar

EXPOSE 8080

ENTRYPOINT ["java","-jar","app.jar"]
