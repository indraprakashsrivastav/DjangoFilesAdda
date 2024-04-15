# DjangoFilesAdda

## Setup

**PYTHON MUST BE INSTALLED ON MACHINE TO RUN THIS PROJECT**

Download Python from [python.org](https://www.python.org/downloads/) and add its path to Environment Variables (Windows).

### Clone the repository

$ git clone https://github.com/indraprakashsrivastav/DjangoFilesAdda.git

$ cd DjangoFilesAdda

### Create and activate a virtual environment

$ python -m venv env

**Activate it on Windows**

$ env/Scripts/activate

**Activate it on Linux/Mac OS**

$ source env/bin/activate

### Install dependencies

(env)$ pip install -r requirements.txt

*Note the `(env)` in front of the prompt. This indicates that this terminal session operates in a virtual environment.*

### Migrate the database

(env)$ python manage.py migrate

### Run the server

(env)$ python manage.py runserver

And navigate to [http://127.0.0.1:8000/](http://127.0.0.1:8000/).
