# Polls app
Polling app

## Installation
- Create a directory and cd into it
```console
$ mkdir myapp
$ cd myapp
```

- Clone this repository
```console
$ git clone "https://github.com/SharathKumarK06/pollapp"
```

- Create a virtual environment and install dependencies
```console
$ python3 -m venv venv
$ source venv/bin/activate
$ pip install -r pollapp/requirements.txt
```

- Add app into project: Add `pollsapp.apps.PollsappConfig` into `INSTALLED_APPS`
  list in `settings.py` file in project directory `myapp`
```python3
...
INSTALLED_APPS = [
    'pollsapp.apps.PollsappConfig',
...
```

- Run the app
```console
python manage.py runserver
```
