# Как развернуть приложение на сервере


## План:

1. Получить доступ на сервер
2. Создать пользователя app (под root нельзя запускать приложение)
3. Установить Docker & Docker-compose
4. Обернуть в docker image frontend и запушить в docker hub
5. Обернуть в docker image backend и запушить в docker hub
6. Написать docker-compose.yaml конфиг
7. Закинуть docker-compose.yaml на сервер и скачать все репозитории
8. Настроить nginx 
9. Настроить certbot для https соединения
10. Настроить базу на сервере
11. Настроить тома/volumes для картинок

