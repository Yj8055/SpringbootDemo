FROM openjdk:8-jdk-alpine
VOLUME /tmp
ADD /target/HelloWordSpringBoot-0.0.1-SNAPSHOT.jar springdemo.jar
ENTRYPOINT ["java","-jar","/springdemo.jar"]
