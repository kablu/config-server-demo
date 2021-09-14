#Start with a base image containing Java runtime
FROM openjdk:8-slim as build

#Information around who maintains the image
MAINTAINER kabluMandal


# Add the application's jar to the container
COPY target/config-server-demo-0.0.1-SNAPSHOT.jar staging.jar


#execute the application
ENTRYPOINT ["java","-jar","/staging.jar"]