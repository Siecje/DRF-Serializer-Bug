```shell
$ virtualenv venv
$ source venv/bin/activate
$ pip install -r requirements.txt
```

```python
$ python manage.py migrate
$ python manage.py shell
>>> from bug.serializer import CreateUserSerializer
>>> serialized = CreateUserSerializer(data={'username': 'cody', 'password': 'cody'})
>>> serialized.is_valid()
True
```
