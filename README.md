# docker-mongod

Docker image that support external data folder

## Sample usage in docker_compose.yml
```yaml
mongodb:
  image: wpottier/mysql
  environment:
    MONGO_MAJOR: 3.2
    MONGO_VERSION: 3.2.1
  volumes:
    - ./data/mongodb:/data/db
  ports:
    - "27017:27017"
```
