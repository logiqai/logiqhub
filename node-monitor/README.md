# Node Level monitoring

## Features
* Monitor Node level statistics via LOGIQ prometheus connector

## Configuration

* Edit node-stats.json and edit the *"datasources"* section with your prometheus endpoint
* Edit the namespaces you want to monitor - defaults to node-stats

## Steps to import

* Download node-stats.json
* Run logiqctl to import the dashboard json

```
logiqctl create dashboard -f node-stats.json
```

## Screenshot
![image info](./node-dash.png)
