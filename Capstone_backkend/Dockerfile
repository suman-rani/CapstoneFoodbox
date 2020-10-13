FROM openjdk:8
ADD target/docker.jar docker.jar
EXPOSE 8085
ENTRYPOINT ["java","-jar","docker.jar"]
