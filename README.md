### rabbit-prometheus-influx-grafana

# MQTT docker boilerplate: portainer, nginx, certbot, RabbitMQ, Grafana, Prometheus, Telegraf, InfluxDB

#### Добавить пользователя rabbit
`docker exec -it rabbit bash`

`rabbitmqctl add_user test_user test_pass`

`rabbitmqctl set_user_tags test_user 
administrator`

`rabbitmqctl set_permissions -p / test_user "." "." ".*"`


