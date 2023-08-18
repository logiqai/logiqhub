# Apica Ascent cluster monitoring

## Features
* Monitor the deployed Apica Ascent cluster

## Configuration

* Edit logiq.json and edit the *"datasources"* section with your prometheus endpoint
* Edit the name of the dashboard, defaults to Apica Ascent

## Steps to import

* Download logiq.json
* Run apicactl to import the dashboard json

```
logiqctl create dashboard -f logiq.json
```

## Screenshot
![image info](./logiq.png)
