# Blog, реализованный на Django REST framework (DRF)

[![Python Version](https://img.shields.io/badge/python-3.11-brightgreen.svg)](https://python.org)

Простой blog, реализованный на Django REST framework (DRF)

Django REST framework is a powerful and flexible toolkit for building Web APIs.

Some reasons you might want to use REST framework:

The Web browsable API is a huge usability win for your developers.
Authentication policies including packages for OAuth1a and OAuth2.
Serialization that supports both ORM and non-ORM data sources.
Customizable all the way down - just use regular function-based views if you don't need the more powerful features.
Extensive documentation, and great community support.
Used and trusted by internationally recognised companies including Mozilla, Red Hat, Heroku, and Eventbrite.

![Blog на DRF](/blog_drf_img.png)

Клонируем репо

```bash
git clone https://github.com/ajax3101/blog_drf.git
```

Устанавливаем и активируем виртуальное окружение

```bash
    python3 -m venv venv
    . venv/bin/activate
 ```

Устанавливаем модули

```bash
    pip install djangorestframework
    pip install markdown       # Markdown support for the browsable API.
    pip install django-filter  # Filtering support 
```

Или загружаем файл с зависимостями проекта

```bash
 pip install -r requirements.txt
```

Запус приложения

```bash
 python manage.py makemigrations 
 python manage.py migrate
 python manage.py runserver 
```
