FROM openjdk:8
COPY complete/target/gs-maven-0.1.0.jar /usr/app/
WORKDIR /usr/app
EXPOSE 8080
ENTRYPOINT ["java", "-jar", "gs-maven-0.1.0.jar"]
