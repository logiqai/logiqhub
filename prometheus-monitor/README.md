# Prometheus Level monitoring

## Features
* Monitor Promethus, AlertManager via LOGIQ prometheus connector

## Configuration

* Edit for ex: alert-manager.json and edit the *"datasources"* section with your prometheus endpoint
* Edit the namespaces you want to monitor - defaults to container-stats

## Steps to import

* Download for ex: alert-manager.json
* Run logiqctl to import the alert-manager.json

```
logiqctl create dashboard -f alert-manager.json
logiqctl create dashboard -f prometheus-static.json
logiqctl create dashboard -f prometheus.json

```


## Screenshot

![image info](./alert-manager-0.png)
![image info](./alert-manager-1.png)

![image info](./prometheus-static-0.png)
![image info](./prometheus-static-1.png)

![image info](./prometheus-0.png)
![image info](./prometheus-1.png)
