## Configuration
```
MONGO DB
docker-compose up
----------------------

```
### USE MONGO DB
```
docker ps -a
CONTAINER ID   IMAGE          COMMAND                  CREATED             STATUS                      PORTS     NAMES
965cc9730d89   mongo:latest   "docker-entrypoint.s…"   About an hour ago   Exited (0) 51 minutes ago             import-mongo-mongodb-1

docker start 965cc9730d89

optional:
docker ps
 docker exec -it container_ID mongosh -u root -p password_of_mongodb_instance
```

## TASK
```
cd /home/project/fullstack-capstone-project/giftlink-backend/util/import-mongo
-> create .env with .env.sample
npm install
npm start
```