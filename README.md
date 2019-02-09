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
## How to run server
In order to run this server you need to install python(2.7) or higher in your machine(linux/windows).

It is recommended to use vagrant for testing .This will not effect your machine configurations. Here is documentation to install vagrant and [virtual box] (https://www.virtualbox.org/wiki/Documentation)

These instructions assume you have the Udacity-provided Virtual machine

Clone the Udacity Vagrantfile

Go to Vagrant directory and either clone this repo or download and place zip here

`vagrant up` `vagrant ssh`

Connecting vagrant after goto to Shared folders, goto Project Folder The entry point for this project is `finalproject.py` run this file using

`python finalproject.py`

After this if all goes well access your web application from http://localhost:8000
         
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
