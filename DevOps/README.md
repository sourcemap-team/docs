# Как развернуть приложение на сервере


## План:

1. Получить доступ на сервер (желательно по ssh)
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

1) Разделить фронт и бэк на 2 репы
2) Купить сервер
3) Создаем файл dockerFile в корне проекта
4) Создаем .dockerignore
5) docker build -t sourcemapteam/cape-n-coat-client .
6) Создаем нового пользователя на сервере (https://dev.to/atosh502/create-separate-users-in-linux-for-running-applications-4c4o)
7) Устанавливаем Docker (https://docs.docker.com/engine/install/ubuntu/)
8) Создаем пользователя app с паролем
9) Добавить новый ssh-ключ
10) актуализировать зависимости
11) устанавливаем необходимые библиотечки
12) устанавливаем докер
13) логинимся в докере
14) запускаем контейнер
15) создаем файл docker-compose.yml
16) Кладем туда конфиг
17) 
