# java 8
FROM openjdk:8
#use port 8080
EXPOSE 8080

WORKDIR /usr/src/app

# copy content from the project to the image
COPY . .

# build
RUN ./mvnw package

# run
CMD ["java", "-jar", "./target/docker-example-1.1.3.jar"]
