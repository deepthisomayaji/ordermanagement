FROM eclipse-temurin:17

LABEL mentainer="javaguides.net@gmail.com"

WORKDIR /app

COPY  target/email-service-0.0.1-SNAPSHOT.jar  /app/email-service.jar

ENTRYPOINT ["java", "-jar", "email-service.jar"]