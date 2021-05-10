FROM java:8

COPY . /usr/src/funadmin/gen
WORKDIR /usr/src/funadmin/gen

ENTRYPOINT ["java","-Dspring.profiles.active=prod","-jar","funadmin-modules-gen.jar"]
EXPOSE 9202