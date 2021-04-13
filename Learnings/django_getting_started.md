# This is django getting started

1. Make sure you install virtualenv
2. make sure you have install all requirements (python -m pip install -r requirement.txt)
3. use django command line to start a new project (django-admin startproject meeting_planner)
4. cd meeting_planner/
5. run a server (python manage.py runserver)
6. Control+C to stop server

Go to the project folder, run
1. python manage.py startapp website
2. using empty string to configure default page path('',welcome),


Migrations

1. show migrations
   python manage.py showmigrations

2. apply migration
   python manage.py migrate

3. check database (you would need to install sqlite)
   python manage.py dbshell

4. show tables
    .tables

5. show important tables
   select * from django_migrations

6. exit
   .exit

after you have modified or added new model whhich touched database, you need to run
    python manage.py makemigrations

run migration 
    python manage.py sqlmigrate meetings 0001
or
   python manage.py migrate

create super users
    python manage.py createsuperuser