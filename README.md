# pyGhana
Website

This is the source code for the http://pythonghana.org/ website.

To run locally

To Run:

Create a virtualenv called myvenv and launch it (see Note below).

(myvenv) $ pip install -r requirements.txt

(myvenv) $ python miange.py migrate

(myvenv) $ python miange.py makemigrations

(myvenv) $ python miange.py runserver

Copy the IP address provided once your server has completed building the site. (It will say something like >> Serving at 127.0.0.1....), 
then paste the IP address into the URL bar of a browser window and load it to view the site.

How to fork and clone: https://help.github.com/articles/fork-a-repo

How to create a virtualenv: http://simononsoftware.com/virtualenv-tutorial/

Note: It is important that when you create your virtualenv, do not create it in the same folder as the code you downloaded. 
