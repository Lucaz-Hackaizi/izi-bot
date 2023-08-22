# izi-bot
## Base de datos
```sh
docker run -d --name mongodb-container -e MONGO_INITDB_ROOT_USERNAME=root -e MONGO_INITDB_ROOT_PASSWORD=root -p 27017:27017 mongo:latest
```