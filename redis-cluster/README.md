# Redis cluster monitoring

## Features
* Monitor one or more redis clusters via LOGIQ prometheus connector
* Dropdown selector to switch redis running on different namespaces

## Configuration

* Edit redis-cluster-monitoring.json and edit the *"datasources"* section with your prometheus endpoint

## Steps to import

* Download redis-cluster-monitoring.json
* Run logiqctl to import the dashboard json

```
logiqctl create dashboard -f redis-cluster-monitoring.json
```

## Screenshot
![image info](./redis-cluster.png)
