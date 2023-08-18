# Java Spring Boot Application monitoring

## Features
* Monitor Spring Boot Application events via Apica Ascent Prometheus connector

## Configuration

* Edit spring-boot.json and edit the *"datasources"* section with your prometheus endpoint

## Steps to import

* Download the file spring-boot.json
* Run apicactl to import the spring-boot.json

```
logiqctl create dashboard -f spring-boot.json
```

## Screenshot

![image info](./spring-boot.png)
