Flask Web Application README
This repository contains the code for a Flask web application that consists of a login page and a homepage.

Description
The application is built using the Flask framework in Python. It includes two routes:

Home Route (/): This route renders the login page (index.html) of the application.
Homepage Route (/homepage): This route renders the homepage (homepage.html) of the application.
The login page allows users to input their credentials, and upon successful authentication, users are redirected to the homepage.

Installation
To run this Flask application:

Clone this repository to your local machine.
Install Flask if you haven't already. You can install Flask using pip:
Copy code
pip install Flask
Navigate to the project directory in your terminal.
Run the Flask application by executing the following command:
Copy code
python app.py
Once the server is running, open your web browser and go to http://localhost:5000 to access the login page.
File Structure
The main components of this Flask application are:

app.py: This file contains the Python code that defines the routes and configures the Flask application.
templates/ Directory: This directory contains HTML templates used by the application.
index.html: The login page HTML template.
homepage.html: The homepage HTML template.

Usage
Upon accessing the login page (/), users can input their credentials.
After successful authentication, users are redirected to the homepage (/homepage).
The application includes basic routing and template rendering functionality.

Dependencies
Flask: The web framework used to build the application.
