# admin-server

## Installation

Make sure you have the [docker](https://docs.docker.com/get-docker/) installed

cd into project root folder and run:

```bash
docker-compose up
```

In browser go to http://localhost:8080/console to see the Hasura console

If there is no dummy data inside the DB once it is running, copy the content of dummyData.sql file and execute it inside the Hasura console 
http://localhost:8080/console/data/sql
