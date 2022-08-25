<div align="center">

# Django Beginner Projects

In this repository you can find some absolute **beginner Django projects**.

I started learning Django by reading "Django for beginners" by William S. Vincent.<br />
All the projects below come from the book.

[Introduction](#introduction) •
[Project 1](https://github.com/andreaaazo/django-beginner-book/tree/main/helloworld) •
[Project 2](https://github.com/andreaaazo/django-beginner-book/tree/main/pages) •
[Project 3](https://github.com/andreaaazo/django-beginner-book/tree/main/mb) •
[Project 4](https://github.com/andreaaazo/django-beginner-book/tree/main/blog)

</div>

<br />

## Introduction
Django is an open source python web framework used to handle various connections to the DataBase, extract/insert data, manage the requests and a lot of features.  
It's popularity is due to its friendliness to beginners and professionals.  

Django it's the #7 most popular web framework, and it's so robust to be used by the largest websites in the world: Instagram, Bitbucket, Pinterest.

### Projects:
This is an overview of the projects, and what elements we are touching:  

| Project Name  | Project Objectives  | Keywords|
| ------------- |:-------------:|:-----------:|
| hello world   | Basic terminal commands / first Django website / Pipenv | git, terminal, templates, tests, pipenv|
| pages         | URLS / Views / Templates / Django settings | ListView, urlpatterns, Django templates |
| mb            | Models / Database / Templates      |models, Django admin|
| blog          | Models / Database / Django template language / Basic HTML | HTML, CSS, static, Django admin |


<br />

<br />

## Useful commands
### 1. Introduction

Django is the perfect tool to learn the relationships between databases and webservers.  
It's a 'batteries included' framework (it provides some pre-installed functionalities).  
The main focus for this project is to understand the files that Django provides for us.  

<ins>The perfect way to start a project is by doing it in the terminal.</ins>  
I know it could be a little bit challenging and scary using the terminal, but once you start to get along with it; creating projects will be a lot more professional and fast.  

Here below I wrote some **useful zsh terminal commands**:  

**Change directory**
```zsh
cd name_of_the_directory
```
_example: `cd Desktop`_

<br />

**List of the files and folders in the current directory**
```zsh
ls
```
<br />

**Back in the previous directory**
```zsh
cd ..
```
<br />

**Create a folder in the current directory**
```zsh
mkdir name_of_the_folder
```
_example: `mkdir projects`_

<br />

**Remove a file in the current directory**
```zsh
rm name_of_the_file
```
_example: `rm main.py`_

<br />

**Create a file in the current directory**
```zsh
touch name_of_the_file
```
_example: `touch main.py`_

<br />


### 2. Setting up the enviroment
####  • Create the project folder
First of all, we need to create a directory folder where it will be the project.

Open your terminal, and **go to your Desktop** folder by typing:
```zsh
cd Desktop
```
<br />

Once we are in the Desktop directory, we need to **create the project folder**:
```zsh
mkdir name_of_the_project
```
<br />

**Go in the project folder** by typing in the terminal:
```zsh
cd name_of_the_project
```
<br />

#### • Installing the environment

To install the python environment we will use `pipenv`.

_If you haven't installed `pipenv`, type in the terminal `pip install pipenv`._

**Install the environment** by typing:
```zsh
pipenv install
```
<br />

To **use the environment** type:
```zsh
pipenv shell
```
_To exit type `exit`. But don't do it now!_  
<br />

**Install Django** by typing:
```zsh
pip install django
```
<br />

### 3. Setting up Django project
#### • Start Django project
After installing Django, we need to start our project.
To **start the project** type:
```zsh
django-admin startproject name_of_the_project .
```
<br />

After that your folder should have a file called `manage.py`, a folder called `hello_world_project` and two python environment files: `Pipfile` and `Pipfile.lock` (in some cases there will be a file called `db.sqlite3`).
This is the tree of your folder:
```zsh
.
├── Pipfile
├── Pipfile.lock
├── db.sqlite3
├── name_of_the_project
│   ├── __init__.py
│   ├── asgi.py
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
└── manage.py

1 directory, 9 files
```
