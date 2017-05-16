FROM java:8-jre
COPY ./nexus-repo/accountservices-1.0.war /tmp/accountservices-1.0.war
CMD ["java", "-jar", "-Dspring.profiles.active=docker","/tmp/accountservices-1.0.war"]
