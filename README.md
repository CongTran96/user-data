### 1 Install python, django...
1. Check python version:
`python --version`
if not show the python version, Download[here](https://www.python.org) for more

2. Clone project
3. install **virtuallenv**. Open terminal and type follow below:

```
    sudo apt install python-virtualenv
    virtualenv --python=python3.6 myvenv
    source myvenv/bin/activate
```

Third install django:
```
    pip install --upgrade pip
    pip install django~=1.11.0
```

Make Database
```
    python manage.py makemigrations
    python manage.py migrate
```

Then
```
    python manage.py createsuperuser
```
Then type username, and password

Now, running server.
```
    python manage.py runserver
```

4. View json data
go [127.0.0.1:8000/users/](http://127.0.0.1:8000/users) to correct connect server.