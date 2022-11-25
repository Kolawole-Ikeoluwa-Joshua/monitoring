# Prometheus Application Monitoring

To run any of the commands, please ensure you open a terminal and navigate to the path where this readme is located.

## Start Prometheus, Grafana & Dashboards

```
docker-compose up -d prometheus
docker-compose up -d grafana
docker-compose up -d grafana-dashboards
```


## Start the example app you prefer

```
docker-compose up -d --build python-application
```

## Generate some requests by opening the application in the browser

```
http://localhost:81 #Python
```

## Check Dashboards
```
http://localhost:3000


# Prometheus Guide on Kubernetes

Checkout the prometheus guide [here](./kubernetes/readme.md)