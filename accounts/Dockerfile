#Start with a base image containing Java runtime
FROM openjdk:17-jdk-slim

#information about who maintains the image
LABEL maintainer="in708bhugad - Bhushan Gadekar"

#add the jar to application
COPY target/accounts-0.0.1-SNAPSHOT.jar accounts-0.0.1-SNAPSHOT.jar

#start the application
ENTRYPOINT ["java","-jar","accounts-0.0.1-SNAPSHOT.jar"]