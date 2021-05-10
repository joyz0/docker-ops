FROM java:8

COPY . /usr/src/funadmin/monitor
WORKDIR /usr/src/funadmin/monitor

ENTRYPOINT ["java","-Dspring.profiles.active=prod","-jar","funadmin-visual-monitor.jar"]
EXPOSE 9100