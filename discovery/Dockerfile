FROM openjdk:8
VOLUME /tmp

ADD target/*.jar app.jar
RUN sh -c 'touch app.jar'


ENV JAVA_OPTS=""
ENTRYPOINT ["java", "-Djava.security.egd=file:/dev/./urandom", "-jar","app.jar"]