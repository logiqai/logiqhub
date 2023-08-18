# Apica Ascent Level monitoring

## Features
* Monitor overview of logs via Apica Ascent prometheus connector

## Configuration

* Edit filename.json and edit the *"datasources"* section with your prometheus endpoint
* Edit the namespaces you want to monitor 


## Steps to import

* Download for ex: logiq-monitoring.json
* Run apicactl to import the file logiq-monitoring.json

```
logiqctl create dashboard -f logiq-monitoring.json

```

## Screenshot

![image info](./logiq-monitoring.png)

