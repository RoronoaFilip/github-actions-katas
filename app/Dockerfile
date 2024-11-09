FROM amazoncorretto:21
LABEL author="Filip Filchev"
WORKDIR .
COPY libs/*.jar app.jar
EXPOSE 8000
CMD ["java", "-Dcom.sun.management.jmxremote", "-noverify", "${JAVA_OPTS}", "-jar", "app.jar"]