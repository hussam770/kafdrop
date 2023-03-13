FROM adoptopenjdk/openjdk11:ubi
RUN mkdir /opt/app
COPY kafdrop*.jar /opt/app/kafdrop.jar
CMD ["java", "-jar", "/opt/app/kafdrop.jar"]