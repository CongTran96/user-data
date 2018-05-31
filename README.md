### Instruction
This is backend server run in python. This storages username and password.

Make sure you have installed python.
Check python version:
`python --version`
if not show the python version. You must install python like this.Go to [here](https://www.python.org) for more. Just download and run.

First `clone` this

Second install **virtuallenv**, the virtual for django framework. Go to the direct folder of this project. The direction may
like that `~/user-data/...`. Open terminal and type follow below:

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

You need to make first user. Let's create superuser (seem like normal user because I only know this to create user by commandline):

```
    python manage.py createsuperuser
```
Then type username, and password

Now, running server.
```
    python manage.py runserver
```

go [127.0.0.1:8000/users/](http://127.0.0.1:8000/users) to correct connect server.