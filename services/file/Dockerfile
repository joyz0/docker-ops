FROM java:8

COPY . /usr/src/funadmin/file
WORKDIR /usr/src/funadmin/file

ENTRYPOINT ["java","-Dspring.profiles.active=prod","-jar","funadmin-modules-file.jar"]
EXPOSE 9300