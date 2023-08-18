# RabbitMQ monitoring

## Features
* Monitor RabbitMQ via Apica Ascent Prometheus connector

## Configuration

* Edit for ex: rabbitmq.json and edit the *"datasources"* section with your prometheus endpoint
* Edit the namespaces you want to monitor - defaults to rabbitmq

## Steps to import

* Download for ex: rabbitmq.json
* Run apicactl to import the rabbitmq.json

```
logiqctl create dashboard -f rabbitmq.json
```

## Screenshot

![image info](./rabbitmq-1.png)
![image info](./rabbitmq-2.png)

