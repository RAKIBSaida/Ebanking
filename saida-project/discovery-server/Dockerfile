FROM java:8
VOLUME /tmp
ARG JAR_FILE
COPY ${JAR_FILE} discovery-service.jar
ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/discovery-service.jar"]
