## Overview

This Flask application manages a stock portfolio for each user, including the user management aspects of a web application.


## Key Python Modules Used

* **Flask**: micro-framework for web application development which includes the following dependencies:
  * click: package for creating command-line interfaces (CLI)
  * itsdangerous: cryptographically sign data 
  * Jinja2: templating engine
  * MarkupSafe: escapes characters so text is safe to use in HTML and XML
  * Werkzeug: set of utilities for creating a Python application that can talk to a WSGI server
* **pydantic**: data validation and settings management
* **pytest**: framework for testing Python projects
* **pytest-cov**: pytest extension for running coverage.py to check code coverage of tests
* **flake8**: static analysis tool
* **Flask-SQLAlchemy**: ORM (Object Relational Mapper) for Flask
* **Flask-Migrate**: relational database migration tool for Flask based on alembic
* **Flask-WTF** - simplifies forms in Flask
* **email_validator** - email syntax validation library for use with Flask-WTF
* **Flask-Login** - support for user management (login/logout) in Flask
* **Flask-Mail** - Flask extension for sending email
* **requests** - Python library for HTTP
* **freezegun** - library that allows your Python tests to travel through time by mocking the datetime module
* **Gunicorn**: 'Green Unicorn’ is a Python WSGI HTTP Server 
* **psycopg2-binary**: PostgreSQL database adapter for Python

This application is written using Python 3.10.12
