# Andalus Competitive Programming Online Judge (ACPOJ)


It is an automated judge system to run programming contests. It has a mechanism to submit problem solutions, have them judged fully automatically, and provides (web)interfaces for teams, the jury, and the general public.


## Requirements
#### install python3


#### Creating Python Virtual Environment 
### install dependencies
Right there, you will find the requirements.txt file that has all the great debugging tools, django helpers and some other cool stuff. To install them, simply type:

```pip install -r requirements.txt```


## Initialize the database

First set the database engine (PostgreSQL, MySQL, etc..) in your settings files; 
projectname/settings.py . Of course, remember to install necessary database driver for your engine. Then define your credentials as well. Time to finish it up:

If you don't have a database engine or driver, use the default database that is sqlite3. 
Comment the MySQL configuration and uncomment sqlite3 in projectname/settings.py

```python manage.py migrate```

create a superuser, which is super admin/database admin, simply type :

```python manage.py createsuperuser```

and create admin of the system from user table by selecting admin role in django admin site.


### Ready? Go!


```python manage.py runserver```


## Authors


* Mukerem Ali
* Mustefa Kamil
