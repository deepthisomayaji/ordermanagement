FROM eclipse-temurin:17

LABEL mentainer="javaguides.net@gmail.com"

WORKDIR /app

COPY  target/product-service-0.0.1-SNAPSHOT.jar  /app/product-service.jar

ENTRYPOINT ["java", "-jar", "product-service.jar"]