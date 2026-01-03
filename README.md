```
sudo apt update
sudo apt install postgresql-client docker.io docker-compose
```

#Запуск контейнера
```
docker-compose up -d

#Подключение в БД

```
psql -h localhost -p 5432 -U admin -d app_db

