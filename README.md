Steps to be followed :-

1. Install docker and docker-compose 

2. clone this repo

3. go to folder

4. And run "docker-compose up -d"


application --> ip-address:8080
prometheus --> ip-address:9090
alertmanager --> ip-address:9093
grafana --> ip-address:3000

default grafana cred
username: admin
password: admin

application metrics location --> ip-address:8080/actuator/prometheus
demo api --> ip-address:8080/doit


Go to grafana and import dashboard.json file
