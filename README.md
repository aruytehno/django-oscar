#### Fast installation
###### Before installing the files from the project, ensure that your operating system contains these applications:

- [NodeJS](https://nodejs.org) including npm.
- Python including pip.

```bash
$ git clone https://github.com/django-oscar/django-oscar.git
$ cd django-oscar
python3 -m venv oscar
source oscar/bin/activate
rm -r ~/Library/Caches/pip/selfcheck/
pip install --upgrade pip
make sandbox
sandbox/manage.py runserver
```

```text
username: superuser
email: superuser@example.com
password: testing
```

[Oscar settings — django-oscar 3.0 documentation](https://django-oscar.readthedocs.io/en/3.0.0/ref/settings.html#)  
[Settings project](src/oscar/defaults.py)  
[Settings sandbox](sandbox/settings.py)