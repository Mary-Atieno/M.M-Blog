# M.M-Blog

By Mary Atieno

## Installation Requirements

A web browser
A virtual environment
Flask
Internet connection
Terminal if you want to access the app locally through your computer

## Development server

Installation requirements

Clone or download the the app from this link <https://github.com/Mary-Atieno/M.M-Blog.git>

Install a virtual environment in your project folder by running the following commands $sudo apt-get install python3.8-venv and $ python3.8 -m venv virtual.To activate the virtual environment run $ source virtual/bin/activate
To install Flask,run the following command $ source virtual/bin/activate then python3.8 -m pip install flask
Make sure to install all the dependencies needed as written in the requirements file
In the terminal,run the app by running the following command : env FLASK_APP='app:create_app("development")' flask run
Also set up your database: CREATE DATABASE blog; using postgres
Initalize your database by running the following command :env FLASK_APP='app:create_app("development")' flask db init

## Known Bugs

If you run the application in any version of python lower than 3.5.6 you will experience errors...Alot of them

## Technologies Used

python3
Flask
Jinja
HTML
Bootstrap
css
SQLAlchemy
Support and contact details
For assistance and Queries please email <maryatieno@gmail.com>

## Behaviour Driven Development (BDD)

Behaviour Input Output
Load the page On page load Get all blogs, Select between signup and login
Select SignUp Email,Username,Password Redirect to login
Select Login Username and password Redirect to page with blogs that have been posted by writes and be able to subscribe to the blog
Select comment button Comment Form that you input your comment
Click on submit  Redirect to all comments tamplate with your comment and other comments
Subscription Email Address Flash message "Succesfully subsbribed to Christian-Blog"

## License

 MIT License

Copyright (c) [2022] [Mary Atieno]

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
