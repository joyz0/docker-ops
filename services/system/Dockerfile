FROM java:8

COPY . /usr/src/funadmin/system
WORKDIR /usr/src/funadmin/system

ENTRYPOINT ["java","-Dspring.profiles.active=prod","-jar","funadmin-modules-system.jar"]
EXPOSE 9201