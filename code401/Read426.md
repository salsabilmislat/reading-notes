# What we will learn

- Django

The source of this summary [The first link](https://www.djangoproject.com/start/)

The source of this summary [The second link](https://wsvincent.com/how-django-works-behind-the-scenes/)

______________________________________

## Intro to Django

**Django is a Python-based free and open-source web framework that follows the model–template–views architectural pattern. also an advanced Web framework written in Python that makes use of the model view controller (MVC) architectural pattern. Django was created in a fast-moving newsroom environment, and its key objective is to ease the development of complicated, database-driven websites.**

### Models

*A model is the single, definitive source of information about your data. It contains the essential fields and behaviors of the data you’re storing. Generally, each model maps to a single database table.*

### URL dispatcher

*URL dispatch provides a simple way to map URLs to view code using a simple pattern matching language. An ordered set of patterns is checked one by one. If one of the patterns matches the path information associated with a request, a particular view callable is invoked. A view callable is a specific bit of code, defined in your application, that receives the request and returns a response object*

### Templates

*template is a text document or a Python string marked-up using the Django template language. Some constructs are recognized and interpreted by the template engine. The main ones are variables and tags. A template is rendered with a context. Rendering replaces variables with their values, which are looked up in the context, and executes tags. Everything else is output as is.*

    - Variables are surrounded by {{ and }}
    - Filters transform the values of variables and tag arguments.{{ django|title }}
    - Comments {# this won't be rendered #}
    
### Working with forms

*Forms are basically used for taking input from the user in some manner and using that information for logical operations on databases. For example, Registering a user by taking input as his name, email, password, etc. Django maps the fields defined in Django forms into HTML input fields*

### User authentication in Django

> It handles user accounts, groups, permissions and cookie-based user sessions.This section of the documentation explains how the default implementation works out of the box, as well as how to extend and customize it to suit your project's needs.

### The Django admin site

*The Django admin application can use your models to automatically build a site area that you can use to create, view, update, and delete records. This can save you a lot of time during development, making it very easy to test your models and get a feel for whether you have the right data. The admin application can also be useful for managing data in production, depending on the type of website. The Django project recommends it only for internal data management , as the model-centric approach is not necessarily the best possible interface for all users, and exposes a lot of unnecessary detail about the models.*

### Internationalization and localization

*allow a single Web application to offer its content in languages and formats tailored to the audience.*

    1. internationalization
    
        Preparing the software for localization. Usually done by developers.
        
    2. localization
    
        Writing the translations and local formats. Usually done by translators.
        
### Security in Django

*Django has effective protections against a number of common threats, including XSS and CSRF attacks.*

#### Common Threats 

+ Cross site scripting (XSS)
+ Cross site request forgery (CSRF) protection
+ SQL injection protection
+ Clickjacking protection
+ Enforcing SSL/HTTPS
+ Host header validation


### How Django Works Behind the Scenes

**there are two ways Django can be run. Either it runs inside a process of the web server itself - as with mod_wsgi on Apache - or it runs in a completely separate process and receives requests via reverse proxy from the server, as with uwsgi/gunicorn.**
