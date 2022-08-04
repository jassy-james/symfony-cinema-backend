### Сборка образов
docker-compose -f ./docker/docker-compose.yml build

### Запуск контейнера
docker-compose -f ./docker/docker-compose.yml up

### Подключение к контейнеру
docker-compose -f ./docker/docker-compose.yml exec -u www-data php-fpm bash