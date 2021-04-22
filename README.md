# Django-ATM-Project
Creation of an ATM Website using Django, Python, HTML, and CSS

This project used the Django Web Framework, a framework written in Python. 

The two major modules of this ATM Project are admin module and user module.

Admin module has sub menus which can create a new ATM user account, and view ATM machine status.
Information on a user account includes:
1. Account Number
2. PIN
3. Account Name
4. Date of Issue
5. Expiration Date
6. Address
7. Balance
8. Phone Number
9. Card status

User module is what a user would see, and it lets a user:
1. Login
2. Logout
3. Create an account
4. Transfer cash
5. Withdraw cash
6. Show balance
7. Change PIN number
8. Change phone number

The project incorporates database design as correct information must be acquired for each user when they login and complete different actions.

Python is the backbone of Django. It is used for url designations on the website, model-view-controller design pattern, forms, decorators, and admin among others.

HTML and CSS are used in templates for different urls, with a base template that is on every page, and then templates for different urls that extend the basic template
and contain different information based on the function that is supposed to be performed by the user on the specific page. CSS is used in different templates, such as navbar.html,
which shows a navigation bar at the top of the page, and login.html, which has a styled login prompt.
