# Itemcatalog
### Aim :
* The Item Catalog project developing an application that provides a list of items within a variety of categories, as well as provide a user registration and authentication system.

* A User Can Read the data,update,delete the data.This program uses third-party auth with Google. Some of the technologies used to build this application include Flask, Bootsrap and SQLite.

## Technologies used in this project :
* Python
* HTML
* CSS
* Flask
* SQLAchemy
* OAuth
* Google Login
## Needs:
 * Vagrant
 * Udacity Vagrantfile
 * VirtualBox
## Application are Used to run:
* Getting Started
* project make sure that you have proper internet connection.
* Have Vagrant and Virtual Box installed on your machine.
* Unzip the file and put the contents in the vagrant directory.
Steps To run The Vagrant Box:

`` $ vagrant up
   $ vagrant ssh``
   
* To Initialize Database and To initialize the SQLite database

         $ python database_setup.py
         
* To load the initial sporting categories

         $ python lots_of_menu.py
         
* Now materials are added.
* To start the application or to run the project on the server

         $ python finalproject.py
         
* The web app will be running on your localhost at port 5050 (http://localhost:8000/)
* Open the above mentioned link to use the web app.
* You can only view the catalog without signing in.
* To create, update and delete the items in the catlog, sign in using Google+.
* To login using Google+ http://localhost:8000/login to login to the app
* To Use Google Authentication Services
* We will need a client_secret.json file.
* We can create an application to use Google's OAuth service at https://console.developers.google.com. After creating and downloading client_secret.json file, move it to the directory where it is accessible to the project file. This project uses persistent data storage to create a web application that allows users to perform Create, Read, Update, and Delete operations.
