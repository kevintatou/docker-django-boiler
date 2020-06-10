
# docker-django-boiler
Docker django boilerplate

# Requirements
- Docker 
- Python
- Django
- Docker-compose

# Links
- https://docs.docker.com/compose/django/
- https://www.saltycrane.com/blog/2019/01/how-run-postgresql-docker-mac-local-development/
- https://stackoverflow.com/questions/36685980/docker-is-installed-but-docker-compose-is-not-why
- https://yaml-online-parser.appspot.com/
- https://stackoverflow.com/questions/33992867/how-do-you-perform-django-database-migrations-when-using-docker-compose


# Startup instructions

    sudo docker-compose up --build


# Migrate

    sudo docker-compose run web python manage.py migrate


