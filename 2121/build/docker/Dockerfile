FROM openjdk:17.0.2
WORKDIR /usr/src/myapp
COPY ./app.jar /usr/src/myapp/app.jar
ENTRYPOINT ["java","-jar", "/usr/src/myapp/app.jar"]
EXPOSE 8080