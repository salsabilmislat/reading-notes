# What we will learn

- Custom User Model

- DjangoX 

The source of this summary [The first link](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Django/Forms)

The source of this summary [The second link](https://github.com/wsvincent/djangox)

______________________________________


## AbstractUser vs AbstractBaseUser

### Custom User Model Extending AbstractUser

**It is a new User model that inherit from AbstractUser . It requires a special care and to update some references through the settings.py . Ideally it should be done in the begining of the project, since it will dramatically impact the database schema.**


### Custom User Model 

*Creating our initial custom user model requires four steps:* 

* update config/settings.py
* create a new CustomUser model
* create new UserCreation and UserChangeForm
* update the admin

### Superuser

*It's helpful to create a superuser that we can use to log in to the admin and test out log in/log out.*

______________________________________

## DjangoX 

### Installation

*DjangoX can be installed via Pip, Pipenv, or Docker depending upon your setup.*

> Pip 

    $ python3 -m venv djangox
    $ source djangox/bin/activate
    (djangox) $ pip install -r requirements.txt
    (djangox) $ python manage.py migrate
    (djangox) $ python manage.py createsuperuser
    (djangox) $ python manage.py runserver
    # Load the site at http://127.0.0.1:8000

> Pipenv 

    $ pipenv install
    $ pipenv shell
    (djangox) $ python manage.py migrate
    (djangox) $ python manage.py createsuperuser
    (djangox) $ python manage.py runserver
    # Load the site at http://127.0.0.1:8000

> Docker 

    $ docker build .
    $ docker-compose up -d
    $ docker-compose exec web python manage.py migrate
    $ docker-compose exec web python manage.py createsuperuser
    # Load the site at http://127.0.0.1:8000 

*For Docker, the INTERNAL_IPS configuration in config/settings.py must be updated to the following:* 

    # config/settings.py
    # django-debug-toolbar
    import socket
    hostname, _, ips = socket.gethostbyname_ex(socket.gethostname())
    INTERNAL_IPS = [ip[:-1] + "1" for ip in ips]

### Setup 

    # Run Migrations
    (djangox) $ python manage.py migrate

    # Create a Superuser
    (djangox) $ python manage.py createsuperuser

    # Confirm everything is working:
    (djangox) $ python manage.py runserver

    # Load the site at http://127.0.0.1:8000 
