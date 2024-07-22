# Nutrition Facts Tracker
The purpose of the application is to help the user track and plan his daily intake and nutritional needs 
while taking into account his physical activity. I implemented AI in the application in order to make it as easy as 
possible for the user to add new products and trainings to the database. 
Based on the products added to the database, users can create meals and later entire nutritional plans. 
I took care of maintaining the efficiency of all functionalities and views by using the Pytest framework.

# Setup of the app
To install requirements of the project execute the following command:

`$ pip install -r requirements.txt`

Establish connection to a database of your choice. Create migrations and migrate:

`$ python manage.py makemigrations` then `$ python manage.py migrate`

To start the app:

`$ python manage.py runserver`

# Left to do:
- add a meal to a database functionality,
- details view for all meals added to a database,
- add a nutritional plan to a database functionality,
- details view for all plans added to a database,
- execution of a daily goal.