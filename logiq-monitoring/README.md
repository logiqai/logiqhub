# Logiq Level monitoring

## Features
* Monitor overview of logs mvia LOGIQ prometheus connector

## Configuration

* Edit filename.json and edit the *"datasources"* section with your prometheus endpoint
* Edit the namespaces you want to monitor 


## Steps to import

* Download for ex: logiq-monitoring.json
* Run logiqctl to import the file logiq-monitoring.json

```
logiqctl create dashboard -f logiq-monitoring.json

```

## Screenshot

![image info](./logiq-monitoring.png)

