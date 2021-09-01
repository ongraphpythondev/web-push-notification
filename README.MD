# WEB PUSH NOTIFICATIONS

## Description

Web push notifications allow users to opt-in to receive updates to mobile and web applications. And this application is helpful for django application to send push notifications from application. This application uses django-webpush package.

## Setup

The first thing to do is to clone the repository:

```bash
$ git clone https://github.com/ongraphpythondev/web-push-notification.git
$ cd web-push-notification
```

Create a virtual environment to install dependencies in and activate it (Windows Only):

```bash
$ py –m venv venv
$ .\venv\Scripts\activate
```

Create a virtual environment to install dependencies in and activate it:

```bash
$ virtualenv2 --no-site-packages env
$ source env/bin/activate
```

Then install the dependencies:

```bash
(env)$ pip install -r requirements.txt
```

Note the (env / venv) in front of the prompt. This indicates that this terminal session operates in a virtual environment set up by virtualenv2.

Once pip has finished downloading the dependencies:

```bash
(env)$ cd project
(env)$ python manage.py runserver
```

And navigate to [localhost](http://127.0.0.1:8000).
