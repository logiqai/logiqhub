# Kube-Cluster Level monitoring

## Features
* Monitor Kube Pods, Nodes via LOGIQ prometheus connector

## Configuration

* Edit kube-cluster-stats.json and edit the *"datasources"* section with your prometheus endpoint
* Edit the namespaces you want to monitor - defaults to kube-cluster-stats

## Steps to import

* Download kube-cluster-stats.json
* Run logiqctl to import the dashboard json

```
logiqctl create dashboard -f kube-cluster-stats.json
```

## Screenshot
![image info](./kube-cluster-dash.png)
