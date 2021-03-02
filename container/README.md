# Container Level monitoring

## Features
* Monitor container via LOGIQ prometheus connector

## Configuration

* Edit container-stats.json and edit the *"datasources"* section with your prometheus endpoint
* Edit the namespaces you want to monitor - defaults to container-stats

## Steps to import

* Download container-stats.json
* Run logiqctl to import the dashboard json

```
logiqctl create dashboard -f container-stats.json
```

## Screenshot
![image info](./container-dash-0.png)
![image info](./container-dash-1.png)
