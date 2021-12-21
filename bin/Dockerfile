FROM openjdk:11-jre-stretch
ADD target/spring-petclinic-2.2.0.jar spring-petclinic-2.2.0.jar
EXPOSE 8085
ENTRYPOINT [ "java", "-jar", "spring-petclinic-2.2.0.jar" ]