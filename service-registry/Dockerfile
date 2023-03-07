FROM openjdk:11
ARG JAR_FILE=target/*.jar
COPY target/service-registry-0.0.1.jar service-registry.jar
ENTRYPOINT ["java","-jar","/service-registry.jar"]
EXPOSE 8761
