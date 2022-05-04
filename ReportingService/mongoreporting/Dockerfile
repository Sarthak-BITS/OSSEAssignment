FROM adoptopenjdk/openjdk11:ubi
RUN mkdir /opt/app
COPY target/*.jar /opt/app/mongoreporting.jar
CMD ["java", "-jar", "/opt/app/mongoreporting.jar"]
#docker run -d -p 6002:6002 --net=report-net --name reportingservice reportingservice:latest