FROM adoptopenjdk/openjdk11:jdk-11.0.10_9-slim
WORKDIR /opt
COPY target/*.jar /opt/app.jar
ENTRYPOINT exec java $JAVA_OPTS -jar app.jar
