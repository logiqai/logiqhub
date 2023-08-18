# Logiq Query statistics

## Features
* Monitor the overview of Queries via Apica Ascent prometheus connector

## Configuration

* Edit filename.json and edit the *"datasources"* section with your prometheus endpoint
* Edit the namespaces you want to monitor 


## Steps to import

* Download for ex: Query-statistics.json
* Run apicactl to import the file Query-statistics.json

```
logiqctl create dashboard -f Query-statistics.json

```

## Screenshot

![image info](./Query-statistics.png)

