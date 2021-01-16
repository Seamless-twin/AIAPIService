# AIAPIService

## Library Requirement
`Python 3.9`
`Flask >= 1.1.2`
`Celery 5.0.5`

## Redis Limitation
**The current online Redis Database is limited, do switch to a local one to get better result!!!!!**

## Test Environment
```
(venv) E:\Projects\AIAPIService>pip list
Package          Version
---------------- -------
amqp             5.0.2
billiard         3.6.3.0
celery           5.0.5
click            7.1.2
click-didyoumean 0.0.3
click-plugins    1.1.1
click-repl       0.1.6
Flask            1.1.2
itsdangerous     1.1.0
Jinja2           2.11.2
kombu            5.0.2
MarkupSafe       1.1.1
pip              20.3.3
prompt-toolkit   3.0.10
pytz             2020.5
redis            3.5.3
setuptools       51.1.2
six              1.15.0
vine             5.0.0
wcwidth          0.2.5
Werkzeug         1.0.1
```

## How to run
- 1. Create a VENV
- 2. PIP
- 3. Use following command to start a worker
`(venv) PATH_TO_THE_PROJECT\AIAPIService>celery -A app.celery worker`
- 4. By default, the service is running on http://127.0.0.1:5000/
- 5. Click the button on the index.html and view the update
