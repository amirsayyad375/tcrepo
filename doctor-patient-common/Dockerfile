FROM ubuntu:20.04
RUN apt update -y
RUN apt install openjdk-8-jdk -y
ARG JAR_FILE=*.jar
COPY ${JAR_FILE} application.jar
ENTRYPOINT ["java", "-jar", "application.jar"]
