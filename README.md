The following instructions are for installation of HOSPITAL MANAGEMENT APP in Windows 10 environment

Download the zip file and unzip it in required location.

Start the virtual environment with the command 
	python -m venv venv_name

Activate venv with the command 
	.\venv_name\Scripts\activate

Install all requirements from the file requirements.txt with command
	pip install -r requirements.txt

Migrate all the tables in the sqlite database with the commands
	python manage.py makemigrations
	python manage.py migrate

Run the server with
	python manage.py runserver

Hope this command will run the app.

Terminate the server to create super user for the database access
	python manage.py createsuperuser

Register the patients using register menu and traverse through the app

