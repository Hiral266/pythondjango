1. Python installed (python --version)
2. Virtual environment setup
3. python -m venv venv
4. venv\Scripts\activate     # On Windows
5. django-admin startproject helloworld
6. cd helloworld
7. python manage.py startapp core
8. python manage.py runserver
9. http://127.0.0.1:8000/

helloworld/
├── core/
│   ├── views.py       # hello_world() view
│   └── urls.py        # route for ''
├── helloworld/
│   ├── settings.py    # add 'core' to INSTALLED_APPS
│   └── urls.py        # include core.urls

