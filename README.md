# django-todo
A simple todo app built with django

![todo App](https://raw.githubusercontent.com/shreys7/kbagwari035/develop/staticfiles/todoApp.png)
### Setup
To get this repository, run the following command inside your git enabled terminal
```bash
$ https://github.com/kbagwari035/django_todo.git
```
You need to install pip first

For Debian based
```bash
$ sudo apt-get install python3-pip
```
For Redhat Based
```bash
$ sudo yum install pyhon3-pip
```
You need to install virtual environment
```bash
$ sudo pip install virtualenv
```
$ mkdir env
$ virtualenv -p python3 env
$ source env/bin/activate
$ cp ~/django_todo.git/* env
$ cd env
$ python manage.py makemigrations
$ python manage.py migrate
$ python manage.py createsuperuser
$ nohop python manage.py runserver 0.0.0.0:8080 &
