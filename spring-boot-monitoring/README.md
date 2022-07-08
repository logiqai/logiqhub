# Java Spring Boot Application monitoring

## Features
* Monitor Spring Boot Application events via LOGIQ Prometheus connector

## Configuration

* Edit spring-boot.json and edit the *"datasources"* section with your prometheus endpoint

## Steps to import

* Download the file spring-boot.json
* Run logiqctl to import the spring-boot.json

```
logiqctl create dashboard -f spring-boot.json

```

## Screenshot

![image info](./spring-boot.png)
