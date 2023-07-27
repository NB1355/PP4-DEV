## SETUP
1. pip3 install 'django<4'
2. django-admin startproject pp5 .
3. python manage.py migrate
4. pip show django-allauth
5. cp -r /workspace/.pip-modules/lib/python3.8/site-packages/allauth/templates/* ./templates/allauth/
6. python3 manage.py startapp home
7. templates/allauth/base.html

=
python -m pip install Pillow



## RUN

- python3 manage.py runserver
- python3 manage.py createsuperuser

python3 manage.py makemigrations
python3 manage.py migrates

