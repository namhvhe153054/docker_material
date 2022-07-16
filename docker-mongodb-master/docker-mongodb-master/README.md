# docker-mongodb

## Quick Start

To deploy an example HDFS cluster, run:
```
  docker-compose up -d
```

## Access container mongo
```
  docker exec -it IDCONTAINER /bin/bash
```

Run mongoDB in docker have configue username and password
  - MONGO_INITDB_ROOT_USERNAME=admin
  - MONGO_INITDB_ROOT_PASSWORD=admin

## Access mongoDB in server
```
  mongo -u <your username> --authenticationDatabase <your database name>:
```
Then input password
