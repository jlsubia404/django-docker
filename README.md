# django-docker
Configuration of docker compose for Django + PostgreSql develop

# Prerequisites
You need to have previously installed:
- Docker (my local version: 19.03.1, build 74b1e89)
- Git (my local version: 2.21.0 (Apple Git-122))

# Quick start
Follow the next steps
1. Clone the repo: `git clone https://github.com/jlsubia404/django-docker.git`
2. Move to the folder **django-docker**
3. Run: `docker-compose up`
4. Open the http://localhost:8080 in your navigator. Also you can browse http://localhost:8080/polls, then you must see the message "Hello, world, You're at the polls index."
5. If you want to run any command on the running image, you can run: `docker-compose exec web bash` in another terminal.

# Documentation
For more information, you can visit https://docs.docker.com/compose/django/

# Autor
Jorge Subía - @jlsubia

#Licence
GNU GENERAL PUBLIC LICENSE