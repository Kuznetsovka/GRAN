FROM openjdk:latest

ARG JAR_FILE=target/producer-1.0-SNAPSHOT.jar
WORKDIR /opt/app
COPY ${JAR_FILE} producer.jar

# Команда для запуска JAR-файла
CMD ["java", "-jar", "producer.jar"]
