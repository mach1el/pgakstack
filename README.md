# PGAstack

Monitoring your nodes with [Prometheus](prometheus.io) + [Grafana](grafana.org) + [Alertmanager](https://prometheus.io/docs/alerting/latest/alertmanager/) Stack.<br>
Using [Slack](https://slack.com/) to get alert from to keep tracking your system.

## Docker-compose

```
docker-compose up -d
```

## Define slack variable
In alertmanager [config](conf/alertmanager/config.yml) you must define your `(( API ))` and `(( channel ))` for your Slack workspace

## Define alert rules
Refer at [Awesome prometheus alerts](https://awesome-prometheus-alerts.grep.to/) you can customize your rules to [rules](/conf/prometheus/rules.yml)
