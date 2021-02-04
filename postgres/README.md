# Postgres monitoring

## Features
* Monitor postgres

## Configuration

* Edit postgres.json and edit the *"datasources"* section with your prometheus endpoint
* Edit the name of the dashboard, defaults to Postgres

## Steps to import

* Download postgres.json
* Run logiqctl to import the dashboard json

```
logiqctl create dashboard -f postgres.json
logiqctl create dashboard -f postgress_general_stats.json
logiqctl create dashboard -f postgress_database_stats.json
```

## Screenshot
![image info](./postgres.png)
![image info](./pg_general_stats.png)
![image info](./pg_database_stats-1.png)
![image info](./pg_database_stats-2.png)
