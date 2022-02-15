# Django-Rest-Tutorial


### Install Python

Click [Python](https://www.python.org/downloads/windows/)


### Check python and  pip is available after installation

```
pip --version
python3 --version

```

### Install Virtual Environment Creator

```
pip install virtualenv

```

This will help to create isolated light weight python packages in a folder.


### Create a Virtual Environment folder (solated light weight python script folder)

```
virtualenv env

```
This will create Simple folder env which will contain minimal set of python scripts. 
This copy of script will create from the python packages available in the system which is installed in the first step.


### Activate the Virtual Environment and use to create a django project 

In Windows

```
env\Scripts\activate

```

In Linux or mac

```
source env\bin\activate

```

### Now Install Django inside virtual env 


``` 
pip install django
```

### Start Project Using DJango

```
django-admin startproject core .

```

Here ***core*** is the name of project

### Now Run The project 

```
python manage.py runserver

```

