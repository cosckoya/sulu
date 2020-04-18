```
███████╗██╗   ██╗██╗     ██╗   ██╗     ██████╗███╗   ███╗███████╗
██╔════╝██║   ██║██║     ██║   ██║    ██╔════╝████╗ ████║██╔════╝
███████╗██║   ██║██║     ██║   ██║    ██║     ██╔████╔██║███████╗
╚════██║██║   ██║██║     ██║   ██║    ██║     ██║╚██╔╝██║╚════██║
███████║╚██████╔╝███████╗╚██████╔╝    ╚██████╗██║ ╚═╝ ██║███████║
╚══════╝ ╚═════╝ ╚══════╝ ╚═════╝      ╚═════╝╚═╝     ╚═╝╚══════╝
By Cosckoya
```
# Reference Docs
- https://docs.sulu.io/
- https://github.com/sulu
- https://github.com/sulu/skeleton

# Tools
- Docker
- Docker-Compose

# Instructions
· Build Docker Images

``` shell
CMD> docker-compose build
```
· Run Containers
``` shell
CMD> docker-compose up
```
· Access PHP Container
``` shell
CMD> docker-compose exec php bash
```
· Create Sulu Project
``` shell
PHP_CONTAINER_CMD> composer create-project sulu/skeleton .
PHP_CONTAINER_CMD> bin/adminconsole sulu:build dev
PHP_CONTAINER_CMD> chown -R www-data:www-data /var/www/project
```
· GOTO
```
URL: http://localhost/admin/
Login: admin / admin
```