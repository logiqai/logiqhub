# Memcached Level monitoring

## Features
* Monitor Memcached in-memory data store via Apica Ascent prometheus connector

## Configuration

* Edit memcached.json and edit the *"datasources"* section with your prometheus endpoint
* Edit the namespaces you want to monitor - defaults to memcached

## Steps to import

* Download memcached.json
* Run apicactl to import the dashboard json

```
logiqctl create dashboard -f memcached.json
```

## Screenshot
![image info](./memcached-0.png)
![image info](./memcached-1.png)

