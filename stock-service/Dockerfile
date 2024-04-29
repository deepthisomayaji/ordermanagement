FROM eclipse-temurin:17

LABEL mentainer="javaguides.net@gmail.com"

WORKDIR /app

COPY target/stock-service-0.0.1-SNAPSHOT.jar  /app/stock-service.jar


ENTRYPOINT ["java", "-jar", "stock-service.jar"]