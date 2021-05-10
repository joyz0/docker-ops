FROM java:8

COPY . /usr/src/funadmin/auth
WORKDIR /usr/src/funadmin/auth

ENTRYPOINT ["java","-Dspring.profiles.active=prod","-jar","funadmin-auth.jar"]
EXPOSE 9200