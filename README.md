# Django-X

## Topics

1. [Introduction](#introduction)
2. [Requirements](#requirements)
3. [Installation & Configuration](#installation-and-configuration)
4. [License](#license)
5. [Security Vulnerabilities](#security-vulnerabilities)

### Introduction

- This Project are the only Learning purpose to created
- Django-x is the CURD ( Create, Update, Read, Delete ) in the Tweets
- Admin Panel Support by Django-default admin Panel

- Dashboard

### Requirements

- **RAM**: 3 GB or higher.
- **[Python]([text](http://python.org/))**: 3.10 or higher
- **[pip](https://pypi.org/)**: Python Package Managment

### Installation and Configuration

##### Execute these commands below, in order

```bash
pip install uv  # installl fast Python package and project manager

uv venv # Create a virtual environment

.venv\Scripts\activate # Active Env on Windown

```

- install the Django Requirements

```bash
uv pip install -r requirements.txt 
```

- Migration And Super User Create 

```bash
cd main

python manage.py migrate

python manage.py createsuperuser
```

- Enter of Username
- Enter Email Id
- Enter Password
- Enter Password Again
- Super User are the Create

```bash
python .\manage.py runserver        
```

- Run the Server

### License

- This project is MIT licensed.

### Security

email us: thedhruvish@gmail.com
