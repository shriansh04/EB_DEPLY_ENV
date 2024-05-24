# EB_DEPLY_ENV
This repository can be used to upload a django project to Elastic beanstalk.

eb init
eb create django-env
get the url at which the project is deployed and add it to the allowed host list in settings.py
eb deploy
