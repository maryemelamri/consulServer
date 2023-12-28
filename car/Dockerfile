FROM openjdk:17-alpine

WORKDIR /app

COPY target/car-0.0.1-SNAPSHOT.jar /app/car-service.jar

EXPOSE 8086

CMD ["java", "-jar", "/app/car-service.jar"]
