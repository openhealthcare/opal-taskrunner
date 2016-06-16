This is taskrunner - an [OPAL](https://github.com/openhealthcare/opal) plugin for using Celery with OPAL applications.

## ! Important Notice !

This plugin is no longer actively maintiained - as of OPAL 0.6.0 Celery/taskrunner functionality has been made part of OPAL core.


### Installation

Install rabbitmq-server
Install and add django-celery, opal-taskrunner to your installed apps.

Run Python manage.py migrate djcelery

###

Running Celery:

    DJANGO_SETTINGS_MODULE=elcid.settings celery -A taskrunner worker -l info
