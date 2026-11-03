FROM amazoncorretto:8-al2
EXPOSE 8080
WORKDIR /user/src/app
COPY . .
RUN chmod +x ./mvnw
RUN ./mvnw package
CMD ["java", "-jar", "./target/docker-example-1.1.3.jar"]