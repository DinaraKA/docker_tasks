FROM eclipse-temurin:17-jdk-jammy
COPY spring-petclinic /app
WORKDIR /app
RUN ./mvnw dependency:resolve



CMD ["./mvnw", "spring-boot:run"]