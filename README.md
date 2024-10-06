# Student_Management_System

This is a student management system built using Django 4, HTML 5, CSS 3, and Bootstrap 5 with a Bootswatch theme.

Prerequisites :

Ensure you have the following installed on your machine:

1) Python 3.8-3.11: The project is built using Django 4.2.4, which requires a compatible version of Python. For more information on installing Python, refer to Python's official documentation.

2) Visual Studio Code: Recommended IDE for this project. Download it here.


Installation :

1. Create a virtual environment
   
   Navigate to the root directory of the project and run the following command:

        python -m venv venv

3. Activate the virtual environment

       venv\scripts\activate

5. Install the required dependencies
   
   From the root directory, run:
                         
                          pip install -r requirements.txt

7. Run migrations
   
   To set up the database schema, run:

                        python manage.py makemigrations
                        python manage.py migrate


9. Create an admin user
    
   This will allow you to access the Django Admin interface. Run:

                        python manage.py createsuperuser


Run the Application
To start the application, run:
                       python manage.py runserver

