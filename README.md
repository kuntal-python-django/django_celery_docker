# Project Tree For Django Celery using Docker

```
├── .gitignore
├── .env
├── docker-compose.yml
├── Dockerfile
├── core
│   ├── __init__.py
│   ├── asgi.py
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
├── entrypoint.sh (chmod +x entrypoint.sh)
├── manage.py
├── requirements.txt
├── README.md

```


To build and run
```
docker-compose up -d --build
```

Docker Log
```
docker-compose logs -f
```

Celery Log
```
docker-compose logs -f 'celery'
```

[Handling Periodic Tasks in Django with Celery and Docker](https://testdriven.io/blog/django-celery-periodic-tasks/)
