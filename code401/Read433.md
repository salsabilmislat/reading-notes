# What we will learn

- JSON Web Tokens

- DRF JWT Authentication

- Django Runserver Is Not Your Production Server

The source of this summary [The first link](https://jwt.io/introduction/)

The source of this summary [The second link](https://simpleisbetterthancomplex.com/tutorial/2018/12/19/how-to-use-jwt-authentication-with-django-rest-framework.html)

The source of this summary [The third link](https://vsupalov.com/django-runserver-in-production/)

______________________________________

## JSON Web Token

A proposed Internet standard for creating data with optional signature and/or optional encryption whose payload holds JSON that asserts some number of claims.

### Use

In authentication, when the user successfully logs in using their credentials, a JSON Web Token will be returned and must be saved locally (typically in local or session storage, but cookies can also be used), instead of the traditional approach of creating a session in the server and returning a cookie. 

## Structure

* Header

* Payload

* Signature

## JWT Authentication Workflow

JSON Web Token is an open standard for securely transferring data within parties using a JSON object. JWT is used for stateless authentication mechanisms for users and providers, this means maintaining session is on the client-side instead of storing sessions on the server. Here, we will implement the JWT authentication system in Django.

## Django Runserver Is Not Your Production Server
"If you want to run Django in production, be sure to use a production-ready web server like Nginx, and let your app be handled by a WSGI application server like Gunicorn.

If you plan on running on Heroku, a web server is provided implicitly. You don’t have to take care of it. You just need to specify a command to run your application server (again, Gunicorn is fine) in the Procfile."



