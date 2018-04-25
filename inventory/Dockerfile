FROM openjdk:9
VOLUME /tmp
ARG JAR_FILE
ADD ${JAR_FILE} inventory.jar
ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/inventory.jar"]
