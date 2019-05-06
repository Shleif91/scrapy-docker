Init project:
=============
1. Run `docker-compose build`
2. Run `sudo chown -R $USER:$USER .`
3. Run `docker-compose up`

Migrations:
===========
1. Run `docker-compose exec web bash`
2. Run `python manage.py migrate`

Creating admin user
===================
1. Run `docker-compose exec web bash`
2. Run `python manage.py createsuperuser`