This is taskrunner - an [OPAL](https://github.com/openhealthcare/opal) plugin.


### Installation

Install rabbitmq-server
Install and add django-celery, opal-taskrunner to your installed apps.

Run Python manage.py migrate djcelery

###

Running Celery:

    DJANGO_SETTINGS_MODULE=elcid.settings celery -A taskrunner worker -l info
