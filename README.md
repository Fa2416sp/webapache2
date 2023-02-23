Табота Алексей
Группа Вт-523

    "Docker-compose"

просто запуск
docker-compose up

запуск в фоне
docker-compose up -d

подключеник к контейнеру
docker exec -it <container_id> bash

    "Docker"

установка контейнера
docker build -t my-apache2 .

запуск контейнера
docker run -d -v ./htdocs/:/usr/local/apache2/htdocs/ -p 80:80 httpd:2.4

подключеник к контейнеру
docker exec -it <container_id> bash
