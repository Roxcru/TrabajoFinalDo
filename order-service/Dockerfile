FROM eclipse-temurin:17-jre

WORKDIR /app

COPY target/*.jar /app/order-service.jar

EXPOSE 8083

CMD ["java", "-jar", "/app/order-service.jar"]