# Kubernetes Level monitoring

## Features
* Monitor Container, ApiServer, Kube Pods, Node level statistics via LOGIQ prometheus connector

## Configuration

* Edit filename.json and edit the *"datasources"* section with your prometheus endpoint
* Edit the namespaces you want to monitor - defaults to container-stats

## Steps to import

* Download filename.json
* Run logiqctl to import the dashboard json

```
logiqctl create dashboard -f api-server.json
logiqctl create dashboard -f cluster.json
logiqctl create dashboard -f container.json
logiqctl create dashboard -f kube-cluster.json
logiqctl create dashboard -f node.json
```


## Screenshot

![image info](./apiserver-0.png)
![image info](./apiserver-1.png)
![image info](./cluster-0.png)
![image info](./cluster-1.png)
![image info](./container-0.png)
![image info](./container-1.png)
![image info](./kube-cluster.png)
![image info](./node.png)


