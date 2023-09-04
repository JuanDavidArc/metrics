# How to run this project?

### Install docker and docker compose ###
[Here](https://docs.docker.com/compose/install/) you can download it depending your operative system.
### Start the services ###

    docker-compose up

if this one does not work you can use

    docker compose up

### Configuration ###
By default Prometheus is listening the metrics on port 3000 but you can change it in the prometheus.yml in the var targets.

### Go to grafana ###
You are done, go to localhost:3005 , user: admin  pass: admin
