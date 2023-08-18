# Logiq Level monitoring

## Features
* Monitor overview of logs via Apica Ascent prometheus connector

## Configuration

* Edit filename.json and edit the *"datasources"* section with your prometheus endpoint
* Edit the namespaces you want to monitor 


## Steps to import

* Download for ex: Namespace,app-distribution.json
* Run apicactl to import the file Namespace, app-distribution.json

```
logiqctl create dashboard -f Namespace,app-distribution.json

```

## Screenshot

![image info](./Namespace,app-distribution.png)