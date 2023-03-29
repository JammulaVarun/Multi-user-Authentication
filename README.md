# Multi-User Authentication
Multi-User Authentication using Django
    
*   User will be able to register on the website, and then the user will also receive a confirmation email in order to activate his/her account. After that, the user can log in to the system at any time.

## Project Setup :
1. Activating the virtual environment
```
venv\scripts\activate
```
2. Installing packages 
```
pipenv install -r requirements.txt
```
3. Making Migrations
```
python manage.py makemigrations
python manage.py migrate
```
4. Running server
```
python manage.py runserver
```
5. De-activating the virtual environment
```
deactivate
```
    
    
To create a Superadmin :

    py manage.py createsuperuser
    
## Technologies Used :
1.  Front-End
    * HTML
    * CSS (Bootstrap5)
2.  Back-End
    * Python 
3.  Database
    * SQLite3
4.  Framework :
    * Django
