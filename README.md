## World Tour Application Documentation

This document provides instructions on how to use the World Tour application. The application is a simple Django application that allows users to view information about different countries around the world.

### Getting Started

To get started with the World Tour application, you will need to install the following dependencies:

* Python 3.10 or later
* Django 2.2 or later
* PostgreSQL 9.6 or later

Once you have installed the dependencies, you can create a new Django project and application by running the following commands:
django-admin startproject world_tour
cd world_tour
python manage.py startapp countries
This will create a new directory called  `world_tour`  in your current working directory. The  `world_tour`  directory will contain the following files:

*  `manage.py` : This file is used to manage the Django project.
*  `settings.py` : This file contains the configuration settings for the Django project.
*  `urls.py` : This file defines the URL patterns for the Django project.
*  `wsgi.py` : This file is used to configure the WSGI application for the Django project.

The  `countries`  directory will contain the following files:

*  `models.py` : This file defines the models for the Django application.
*  `views.py` : This file defines the views for the Django application.
*  `urls.py` : This file defines the URL patterns for the Django application.

### Configuring the Database

The World Tour application uses PostgreSQL as its database. To configure the database, open the  `settings.py`  file and update the following settings:

*  `DATABASES` : This setting defines the database connection details.
*  `SECRET_KEY` : This setting is used to generate a secret key for the Django application.

### Running the Application

To run the World Tour application, open a terminal window and navigate to the  `world_tour`  directory. Then, run the following command:
python manage.py runserver
This will start the Django development server on port 8000. You can now access the application at http://localhost:8000/.

### Using the Application

The World Tour application allows users to view information about different countries around the world. To view the list of countries, click on the "Countries" link in the navigation bar. This will display a list of all the countries in the database.

Each country in the list has a link to its detail page. To view the detail page for a country, click on its link. The detail page will display information about the country, such as its name, capital city, population, and area.

The World Tour application also allows users to search for countries. To search for a country, enter its name in the search bar and click on the "Search" button. This will display a list of all the countries that match the search criteria.

### Adding Countries

You can add countries to the database by using the Django admin interface. To access the admin interface, open a browser window and navigate to http://localhost:8000/admin/. Then, log in using the username  `admin`  and the password  `admin` .

Once you are logged in, you will see a list of all the models in the Django application. To add a country, click on the "Countries" link. This will display a list of all the countries in the database.

To add a new country, click on the "Add" button. This will open a form where you can enter the details of the country.

The following fields are required for each country:

* Origin 
* Destination
* Nights
* Cost

Once you have entered the details of the country, click on the "Save" button. This will add the country to the database.

### Editing Origin

You can edit countries in the database by using the Django admin interface. To edit a country, click on its link in the list of countries. This will open a form where you can edit the details of the country.

Once you have made the changes to the country, click on the "Save" button. This will update the country in the database.

### Deleting Origin

You can delete countries from the database by using the Django admin interface. To delete a country, click on its link in the list of countries. This will open a confirmation dialog.

Click on the "Delete" button to delete the country from the database.
