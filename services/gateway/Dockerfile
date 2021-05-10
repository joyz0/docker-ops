FROM java:8

COPY . /usr/src/funadmin/gateway
WORKDIR /usr/src/funadmin/gateway

ENTRYPOINT ["java","-Dspring.profiles.active=prod","-jar","funadmin-gateway.jar"]
EXPOSE 8080