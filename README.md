# Basic-Todo-Flask
================
Basic-Todo-flask is a simple app made to perform basic crud operations on a database, includes bootstrap. This app can be used to add,update,view and delete todo.

Flask extensions used:

	* Flask-SQLAlchemy
	* Flask-WTF

Install
-------
Its advised that you use virtualenv or equivalent.

To setup the virtual python environment and activate it:

	virtualenv venv
	. venv/bin/activate

Download and install requirements:

	clone the repository
	pip install -r requirements.txt

Database setup
-------------------
SQLite is used as default for development, any DB can be swapped in that uses SQLAlchemy.

To create the DB run the create-database.py file:

	python create-database.py

Running the app
---------------
Once the database is created run the run.py file to start the development server, then just browse to the serverip using port 5000:

	python run.py
	http://serverip:5000/

