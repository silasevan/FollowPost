# Step in development 
##  Day1(24/08/2024)
### 1. Installing virtual enviroment and flask. 
#### python -m venv followpost
#### activate virtual environment - venv\Scripts\activate
#### install flask -  pip install flask
#### create a app directory and __init__.py to turn it to a package
#### In the app directory a create a routes.py file which is serving url views
#### i create the first route and render a index file from a template directory.
#### In the project directory I created a microblog.py file to serve the application by import app from app.
### I also created a .flaskenv file to serve my environment variable.
#### I created a base.html file to serve the navigation page which we be inherited by the index and othe pages.
#### i created a fake users, post json file to implement the users, post and login. 
#### I install flask-wtf for forms input
#### I created a config.py file at the project directory for configuration and secret files