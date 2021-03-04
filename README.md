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



[Django Celery Redis Without Docker](https://stackabuse.com/asynchronous-tasks-in-django-with-redis-and-celery/)
[Without Docker Code Sample](https://github.com/amcquistan/image_parroter)




## How to check and configer RabbitMQ

[Help Rabbitmq](tecadmin.net/install-rabbitmq-server-on-ubuntu)
```
sudo systemctl status rabbitmq-server
```

## How to check and configer Redis
```
sudo systemctl status redis-server
sudo systemctl restart redis-server
To run ==> redis-server
```




