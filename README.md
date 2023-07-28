# docker_compose_module_e410
Ссылка Django образа: https://hub.docker.com/layers/pavelsdv/testrep/projectcompose_web/images/sha256-56563910c9a62bd6271ebe69c8eb20e899db1b7fe6c8e4d35656501a2dc7edba?context=repo

Ссылка Nginx образа:
https://hub.docker.com/layers/pavelsdv/testrep/projectcompose_nginx/images/sha256-cf9a1ee3b46579b60d2cb5d5adf8192dc011da7121205ca17dd3ce9e53f24893?context=repo

Команда для установки: docker-compose -f docker-compose.yml up -d --build

http://127.0.0.1:1337/admin/

DJANGO_SUPERUSER_USERNAME=admin
DJANGO_SUPERUSER_PASSWORD=admin
