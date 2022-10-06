# Logiq Level monitoring

## Features
* Monitor overview of logs mvia LOGIQ prometheus connector

## Configuration

* Edit filename.json and edit the *"datasources"* section with your prometheus endpoint
* Edit the namespaces you want to monitor 


## Steps to import

* Download for ex: logs-overview.json
* Run logiqctl to import the file logs-overview.json

```
logiqctl create dashboard -f logs-overview.json

```

## Screenshot

![image info](./logs-overview.png)