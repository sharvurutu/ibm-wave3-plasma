FROM openjdk:11

ADD ./target/document-crawler-service-0.0.1-SNAPSHOT.jar /event/src/document-crawler-service-0.0.1-SNAPSHOT.jar
EXPOSE 8900
WORKDIR event/src
ENTRYPOINT ["java","-jar","document-crawler-service-0.0.1-SNAPSHOT.jar"]