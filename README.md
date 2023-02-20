# Weather-Application
A weather update app is an app that enables users to search for weather information for cities and returns the necessary weather information for those cities.

First main task is to create a virtual environment for the project, this virtual environment will help us manage the project’s dependencies very easily:

$ python -m venv project
Since we will install all our dependencies in the virtual environment, let us activate it. On Windows:

$ .\project\Scripts\activate
Linux/macOS:

$ source project/bin/activate

# Creating the Main Project and the App
Now that we are done with the installations, let's create the project:

$ django-admin startproject weatherapplication
$ cd weatherapplication
After you cd into weatherapplication project, create the application:

$ python manage.py startapp weatherupdates


Finally to run the applcation:
$ python manage.py runserver
