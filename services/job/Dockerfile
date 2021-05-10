FROM java:8

COPY . /usr/src/funadmin/job
WORKDIR /usr/src/funadmin/job

ENTRYPOINT ["java","-Dspring.profiles.active=prod","-jar","funadmin-modules-job.jar"]
EXPOSE 9203