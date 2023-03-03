# Django Blog

This is a simple blog application built using Django web framework. The application is deployed on Heroku and can be accessed at https://djang2-blog.herokuapp.com/.


# Features

1. Users can create their user account.
2. Users can login .
3. Users can log outs.
4. user can signup.
5. Webpages are mobile responsive.
6. Users can view their commit.
7. user can like or unlike a cooment.


# Files & Directories
1. capstone - project directory.
2. utils.py - Contains all Django helper functions used in views.py.
3. urls.py - This file handles all the URLs of the project.
4. manage - main application directory.
5. static - contains all static content.
6. css - Contains all css files for styling the webpages.
7. js - Contains all javascript files used in the application.
8. img - Contains all image files used in the application.
9. templates/djangoblog Contains all application templates.
10. index.html - Home page template.
11. base.html - Base template for all pages except login & register page.
12. redister.html - Base template for login & register page.
13. login.html - Login user page.
14. admin.py - Contains some models for access to the Django administrator.
15. models.py - All models used in the application are created here.
16. urls.py - This file handles all the URLs of the web application.
17. views.py - This file contains all the application views.
18. requirements.txt - This file contains all contains all the python packages that needs to be installed to run this web application.
19. manage.py - This file is used basically as a command-line utility and for deploying, debugging, or running our web application.

# Justification
1. Mobile responsive webpages.
2. More complex models.
3. Converts html template to downloadable pdf.
4. Fully framework application

# Installation
1. Install project dependencies by running py -m pip install -r requirements.txt.
2. Run the commands py manage.py makemigrations and py manage.py migrate in the project directory to make and apply migrations.
3. Create superuser with py manage.py createsuperuser. This step is optional.
4. Run the command py manage.py runserver to run the web server.
5. Open web browser and goto 127.0.0.1:8000 url to start using the web application.

yo can see my website: https://djang2-blog.herokuapp.com/


