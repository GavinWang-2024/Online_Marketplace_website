# Online Marketplace Website


## Project Description
Online marketplace website built using Django. It allows users to browse, buy, and sell items, as well as communicate with each other through a built-in messaging system. Project includes user authentication, item management, and a user dashboard.


## Installation

Copy code
`git clone https://github.com/GavinWang-2024/Online_Marketplace_website.git`
`cd Online_Marketplace_website`

Install dependencies:
`pip install -r requirements.txt`

Run migrations:
`python manage.py migrate`

Create a superuser:
`python manage.py createsuperuser`

`Run the development server:`
python manage.py runserver

Usage

Navigate to http://127.0.0.1:8000/ in your web browser to access the homepage. Users can sign up, log in, and start browsing items. To add new items, users need to log in and navigate to the "New item" section. Messages can be sent through the built-in conversation system accessible via the "Inbox" link. Admin functionalities and user dashboards are available for managing items and user information.

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Django](https://img.shields.io/badge/Django-4.1-green)
![License](https://img.shields.io/badge/License-MIT-yellow)
