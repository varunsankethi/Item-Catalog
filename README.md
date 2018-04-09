# Item Catalog Project - Restaurant Menu App

The Restaurant Menu App provides a list of restaurants and its menus.
It allows you to perform CRUD operations on your restaurants.
Login has been implemented using Google OAuth Sign-In

## Softwares used
- sqlite
- vagrant
- python 
- html
- css
- git

## Installation Steps

1. 'fork' the project from github
2. From a terminal like git-back, install the vagrant virtual machine using `vagrant up`
3. Once the vagrant machine is up, use `vagrant ssh` on a unix like machine and use `winpty vagrant ssh` on a windows machine
4. Once the virtual machine is up, navigate to the restaurant-project directory
5. Run `python database_setup.py` to set up the sqlite database
6. Run `python newLotsOfMenus.py` to set up some data in the database created in step 5
7. Run `python finalProject.py` to start the server
8. Go to 'localhost:5000/restaurants'. This is the index page of the application.
9. Login using google account and perform CRUD operations