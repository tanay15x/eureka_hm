FROM openjdk:17-jdk-alpine

EXPOSE 8761

COPY ./target/eurekaserver.jar eurekaserver.jar

ENTRYPOINT ["java","-jar","eurekaserver.jar"]
 