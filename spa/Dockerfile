FROM maven:latest

COPY . /spa/src/app
WORKDIR /spa/src/app

RUN mvn clean package

EXPOSE 8888

ENTRYPOINT ["java","-jar","target/spa-1.0.jar"]
