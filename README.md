# docker_compose_module_e410
Ссылка Django образа:
https://hub.docker.com/layers/pavelsdv/testrep/projectcompose_web/images/sha256-dd74af69cd7eab088d0354883b1bc66ec3b0bf214e2c8d7a8a0f355ae74b94c7?context=repo

Ссылка Nginx образа:
https://hub.docker.com/layers/pavelsdv/testrep/projectcompose_nginx/images/sha256-0d048d68a9124ec24ac1365799ee5ba76f9469d7e0846183efd24601eeb03c17?context=repo

Команда для запуска проекта из директории с файлом docker-compose.yml: sudo docker-compose -f docker-compose.yml up -d --build

Админ-панель по адресу: http://127.0.0.1:1337/admin/

Для входа в админ-панель создать суперпользователя: sudo docker-compose run web python3 manage.py createsuperuser
