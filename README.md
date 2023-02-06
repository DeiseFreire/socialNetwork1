# Python on Replit

This is a template to get you started with Python on Replit. It's ready to go so you can just hit run and start coding!

## Running the repl

1. Setup a new secret environment variable (the lock icon) where the key is `SECRET_KEY` and the value is
   a randomly generated token of 32 bits of randomnese. To generate such a token type this into the shell and hit Enter:
```
python
import secrets
secrets.token_urlsafe(32)
```
2. Hit run!

See this 1 minute video for a walkthrough: [https://www.loom.com/share/ecc4e738149f4d1db3bcff01758b3e71](https://www.loom.com/share/341b5574d12040fb9fcbbff150777f1c)

## Installing packages

To add packages to your repl, you can just import directly in the file you want to use the package in, and it will automatically be installed when you press the run button. Like below:
```python
import math
import pandas as pd
```

You could also install packages by using the Replit packager interface in the left sidebar.

## Help

If you need help you might be able to find an answer on our [docs](https://docs.replit.com) page. Feel free to report bugs and give us feedback [here](https://replit.com/support).

## Nome do projeto:
socialNetwork 

### Replit
https://socialnetwork1.deisefreire2022.repl.co/

### Comandos 
pip install django-allauth django-crispy-forms
python -m pip install --upgrade pip command.
django-admin startproject socialnetwork .
cd .
python manage.py startapp social 
python manage.py startapp landing
python manage.py makemigrations
python manage.py migrate
python manage.py createsuperuser
pip install django-allauth
python manage.py runserver
pip install Pillow
pip install django-allauth
github.com/pennersr/django-allauth/ree/master/allauth
source env/bin/activate
*source venv/bin/activate
npm init -y #cria o package json

### Configurações 

INSTALLED_APPS = [
    'django.contrib.sites',
    'social',
    'landing',
    'crispy_forms',
    'allauth',
    'allauth.account',
    'allauth.socialaccount',
]

AUTHENTICATION_BACKENDS = [
    # Needed to login by username in Django admin, regardless of `allauth`
    'django.contrib.auth.backends.ModelBackend',

    # `allauth` specific authentication methods, such as login by e-mail
    'allauth.account.auth_backends.AuthenticationBackend',
]

SITE_ID = 1


TEMPLATES = [
'DIRS': [os.path.join(BASE_DIR, 'templates')],
]

socialNetwork > django_project > settings.py
STATIC_URL = '/static/'
CRISPY_TEMPLATE_PACK = 'bootstrap4'
LOGIN_REDIRECT_URL = 'post-list'
ACCOUNT_EMAIL_REQURED = True
EMAIL_BACKEND = 'django.core.mail.backends.console.EmailBackend'

     
### Arquivos criados

localhost:8000/admin/social/post/add/

socialnetwork/landing/templates/landing/index.html # criado arquivo index.html

socialnetwork/landing/templates/landing/base.html # criado arquivo base.html

socialnetwork/landing/templates/landing/navbar.html # criado arquivo navbar.html

socialnetwork/landing/urls.py # criado arquivo urls.py

socialnetwork/social/urls.py # criado arquivo urls.py


### Links

https://docs.djangoproject.com/en/4.1/

https://getbootstrap.com/docs/5.0/getting-started/introduction/

https://getbootstrap.com/docs/5.0/components/buttons/

https://getbootstrap.com/docs/5.0/components/navbar/

https://getbootstrap.com/docs/5.0/components/spinners/


### Páginas criadas

https://socialnetwork1.deisefreire2022.repl.co/
/accounts/signup/
/accounts/login/
/admin/
/admin/social/post/add
/social/
/social/post/1

### Testes na página

E-mail*
example123@example.com
Username*
TestUser
Password*
111
Password (again)*
111

#### 1° teste
admin/social/post/add
Body: my first post 
Created on :
Author: admin
SAVE
ADD POST
Body: second post 
admin Nov. 17, 2022, 12:33 p.m.
Created on:
Author: admin
SAVE
#### 2° teste
Add a Post!
Hi!!
[Submit!] <- botão enviar
Hi!!
admin Nov. 18, 2022, 6:16 p.m
Hello!!
admin Nov. 18, 2022, 6:16 p.m


