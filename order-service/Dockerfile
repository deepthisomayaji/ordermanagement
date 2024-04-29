FROM eclipse-temurin:17

LABEL mentainer="javaguides.net@gmail.com"

WORKDIR /app

COPY  target/order-service-0.0.1-SNAPSHOT.jar  /app/order-service.jar

ENTRYPOINT ["java", "-jar", "order-service.jar"]