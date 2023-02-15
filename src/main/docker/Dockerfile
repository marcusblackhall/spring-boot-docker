FROM rockylinux:9
ADD maven/spring-boot-docker-0.0.3-SNAPSHOT.jar app.jar
RUN yum -y install java-1.8.0-openjdk
EXPOSE 8080
ENTRYPOINT ["java","-jar","app.jar"]