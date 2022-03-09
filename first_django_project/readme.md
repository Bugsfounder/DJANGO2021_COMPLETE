# Creating Django Project | Python Django

## Starting Our Project :

#### <strong> Step 1: </strong> Open Windows Power Shell.

#### <strong> Step 2: </strong> Open the directory in which you want to start the project.

```
cd <DIR_NAME>
```

#### <strong> Step 3: </strong> Type the ‘ls’ command in this directory and then type django-admin to check whether Django is correctly installed or not. If you can see a list of commands after typing django-admin, then you have installed Django properly.

#### <strong> Step 4: </strong>Type the command given below and press enter:

django-admin startproject <PROJECT_NAME>

```
django-admin startproject mysite
```

In the above code, django-admin is a utility to which we have passed an argument, i.e., startproject, and then we have named our project as mysite. You can use any other name for your project except the name of built-in modules such as test, Flask, Django, etc. That way, you can get away with some weird errors that might occur due to import conflicts

Now, we have successfully generated our first Django project - mysite.

Open this project in any IDE, and you will see that Django has created a folder called mysite. Also, you will notice that inside this folder, we have various files such as manage.py, settings.py, urls.py, etc.

Now, let’s discuss what these files are?

---

#### What Is **init**.py?

Django generates this file for us. It is mandatory to have an **inti**.py file in a directory to denote that the project is a python package and can be imported into other files. This file usually remains empty.
If this file gets missing, you will see a “package not found error” in the absence of this file.

---

---

#### What Is settings.py?

This is the core file of our Django projects.
It contains the configuration values which are needed by web apps to work properly, such as database settings, static files location, template location, etc. We will keep coming to this file to edit the project configuration throughout this course.

---

---

#### What is urls.py?

Url declaration and mapping are made under this file.

---

---

#### What is wsgi.py?

WSGI stands for web-server gateway interface.
WSGI is a specification that describes the communication between a web server and a web application.

---

---

#### What is manage.py?

Command-line utility for performing administrative tasks.
We will be using manage.py frequently while developing a Django project.

---

---

### Starting Our Django Server:

Okay, so fun time now. After successfully creating our Django project, it’s time to start our server so that we can be sure that the installation works and proceed with the further development of our project.

##### Step 1: Open the terminal. It is up to you to use the terminal of your IDE or Windows Power Shell/Linux Terminal.

##### Step 2: Fire the command given below and press enter:

```
python manage.py runserver
```

##### Now, click on http://127.0.0.1:8000/, and you will be redirected to a congratulations web page.
