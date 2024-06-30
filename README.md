## Тестовое задание
## Ansible Role, запускающий docker-compose на удаленном сервере
Роль install-docker-compose обновляет пакеты и устанавливает docker, docker-compose. Роль webserver копирует Dockerfile с php приложением, nginx конфиг, php.ini и docker-compose.yaml, а также собирает докерфайл и запускает сервисы, использеутся модуль comunity.docker.docker_compose_v2
