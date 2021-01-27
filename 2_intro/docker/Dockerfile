FROM openjdk:11
WORKDIR /usr/src/myapp
COPY ./SimpleApp/target/demo-0.0.1-SNAPSHOT.jar /usr/src/myapp/app.jar
EXPOSE 8080
CMD ["java", "-jar", "app.jar"]
