# Base Image
FROM openjdk:8

# Copy the Atmosphere Jar Inside Container Image. 
COPY target/spring-boot-sample-atmosphere-1.4.0.BUILD-SNAPSHOT.jar	/usr/src/myapp/

# Working DIR
WORKDIR /usr/src/myapp

# Excute the Atmosphere Chat Code
CMD ["java", "-jar", "spring-boot-sample-atmosphere-1.4.0.BUILD-SNAPSHOT.jar"]
