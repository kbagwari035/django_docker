# django-todo
A simple todo app built with django

![todo App](https://github.com/kbagwari035/django_todo.git/main/staticfiles/todoApp.png)
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
```bash
$ mkdir env
```
```bash
$ virtualenv -p python3 env
```
```bash
$ source env/bin/activate
```
```bash
$ cp ~/django_todo.git/* env
```
```bash
$ cd env
```
```bash
$ python manage.py makemigrations
```
```bash
$ python manage.py migrate
```
```bash
$ python manage.py createsuperuser
```
```bash
$ nohop python manage.py runserver 0.0.0.0:8080 &
```
