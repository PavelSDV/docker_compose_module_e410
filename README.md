# docker_compose_module_e410
Ссылка Django образа:
https://hub.docker.com/layers/pavelsdv/testrep/projectcompose_web/images/sha256-7990c2b890a62fbbe160bdcd3e91f6855ff642a9b3b7c3990fd9aac9eab50124?context=repo

Ссылка Nginx образа:
https://hub.docker.com/layers/pavelsdv/testrep/projectcompose_nginx/images/sha256-d74f69f3275c72273c6b3e782b87c026c3208f6dd66e49da6c2cb11bf717fc90?context=repo

Команда для запуска проекта из директории с файлом docker-compose.yml: sudo docker-compose -f docker-compose.yml up -d --build

Админ-панель по адресу: http://127.0.0.1:1337/admin/

Для входа в админ-панель создать суперпользователя: sudo docker-compose run web python3 manage.py createsuperuser
