Набор LAMP для запуска Битрикс Управление Сайтом.

Apache + PHP + MySQL + Xdebug + phpMyAdmin

http://localhost:8090 - веб-сервер apache
http://localhost:8090/bitrixsetup.php - установочный скрипт битриска
http://localhost:8091 - phpmyadmin

Данные для подключения к базе:

хост: localhost
пользователь: docker
пароль: docker
база данных: docker


Запуск:

1. Скопируйте .env.dist в .env
2. Выставите права доступа на запись в папку public
2. В консоли выполните команду:
`
docker compose up -d
`
3. Откройте в браузере http://localhost:8090/bitrixsetup.php

