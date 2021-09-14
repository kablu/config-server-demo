#Start with a base image containing Java runtime
FROM openjdk:8-slim as build

#Information around who maintains the image
MAINTAINER kabluMandal

# Add the application's jar to the container
COPY /home/runner/work/config-server-demo/config-server-demo/config-server-demo/target/config-server-demo-0.0.1-SNAPSHOT.jar config-server-demo-0.0.1-SNAPSHOT.jar


#execute the application
ENTRYPOINT ["java","-jar","/config-server-demo-0.0.1-SNAPSHOT.jar"]