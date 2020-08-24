# College Queries is a Web-Application Using Python's web framework: Flask

### List of contents

- [Introduction](#introduction)
- [Working](#working)
- [Installation](#installation)
- [Running](#running)


## Introduction
---
[(Back to top)](#list-of-contents)
College Queries is a web application developed using flask as backend and HTML , CSS for the frontend.The website provides authentication facilities to the users and let them track questions asked by them.  The web application allows user to register and then login into the website and ask any query they have reagarding college/University/Course they opted for and the experts in that field can answer the Query. All the answered question are also present in home page.The website solves the challenges faced by freshers who are new to college by providing centralised portal for asking doubts.  



## Working
---
[(Back to top)](#list-of-contents)

The steps involved in creating the website.

+ The backend has been developed in Flask and many extensions of flask like [Flask_SQLAlchemy](http://packages.python.org/Flask-SQLAlchemy), [Werkzeug](http://werkzeug.pocoo.org/), [Flask_Login](https://flask-login.readthedocs.io/) and some others.  

+ The Frontend involves the usage of HTML and CSS. The frontend consists of Login and Registration forms along with other important components like navigation bars, footer and home page. 

+ Password hashing has been implemented using [Werkzeug](http://werkzeug.pocoo.org/) a flask extension that implements password hashing . Password hashing is a complicated topic that should be left to security experts, but there are extensions like werkzeug that implement all that logic in a way that is simple to be invoked from an application.

+ Login and Registration and other authentication related parts are handled using [Flask_Login](https://flask-login.readthedocs.io/). This extension manages the user logged-in state, so that for example users can log in to the application and then navigate to different pages while the application "remembers" that the user is logged in.

+ Sqlite database is being used to store the mappings of the Questions to the asker , anwered by expert and its answer. [Flask_SQLAlchemy](http://packages.python.org/Flask-SQLAlchemy) an ORM tool that provides methods to perform CRUD operations without having to write raw SQL statements is used to write and read the data from the sqlite database.

+ Users can have a look at the answered queries stored in the database at home page in the website. Admin can promote some users to experts who can then answer queries. Queries would be posted to them in unanswerd questions section.

 
## Installation
---
[(Back to top)](#list-of-contents)

- Install  required packages using pip or any other method specified in requirement.txt :
  - pip3 intall -r requirement.txt
- Run the application using :
  - flask run




## Running

- snapshots of the working project

- Home 
![img](https://imgur.com/QCSqmWR.png)

- Register
![img](https://imgur.com/fjEZk80.png)

- Login
![img](https://imgur.com/OKjMbO8.png)

- Ask Question
![img](https://imgur.com/nyqlxDn.png)

- Answer Question
![img](https://imgur.com/U5LJDnh.png)

- About Users
![img](https://imgur.com/HmVb9Qd.png)
