# OHTK API
The OHTK API controls the mobile app and the management system. 

### What you'll need
- python 3.8 or greater
- pip
- Laravel Valet (if using a proxy over HTTP)

#### Install
Get the latest version of ohtk-api

```git clone https://github.com/onehealthtoolkit/ohtk-api.git```

Go to the newly created directory

```cd ~/podd-api```

It is recommend that you install the package requirements via a virtual environment. 

For example:

```python -m venv pickavirtualenvname```

```source pickavirtualenvname/bin/activate```

#### Install Requirement Packages
Install all requirement packages

```pip install -r requirements.txt```

#### Postgres Server and Databases
Start a Postgres Server

Create a database

Add username/password credentials for a database user

Use these credentials in settings.py

#### Run Manage.py Commands

This will do a bunch of stuff

```python3 ./manage.py migrate```

This will create a Django super admin user

```python3 ./manage.py create superuser```

#### Start Local Servers
Start OHTK API Local Server

``` python ./manage.py runserver```

Start Proxy

```valet proxy opensur http://127.0.0.1:8000 --secure```

Navigate to ```https://opensur.test/admin/```