
# Django_Redis



Kindly ensure you have the following installed on your machine:

- [ ] [Python 3]
- [ ] [Pipenv]
- [ ] [Redis]
- [ ] [Git]()
- [ ] An IDE or Editor of your choice

### Running the Application

1. Clone the repository
```
$ git clone https://github.com/ro6ley/django-redis.git
```

2. Check into the cloned repository
```
$ cd django-redis
```

3. If you are using Pipenv, setup the virtual environment and start it as follows:
```
$ pipenv install && pipenv shell
```

4. Install the requirements
```
$ pip install -r requirements.txt
```

4. Configure Redis configuration in `django_redis_demo/settings.py`

5. Start the Django API
```
$ python manage.py runserver
```

6. Send requests to `http://localhost:8000/api/items`
